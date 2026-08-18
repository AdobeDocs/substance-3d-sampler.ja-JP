---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/scripting-and-development/create-a-plugin-with-python-and-qml.html"
breadcrumb-title: ''
description: Substance 3D Sampler用のPythonおよびQMLでプラグインを作成し、カスタムユーザーインターフェイスを構築して機能を拡張する方法について説明します。
helpx_creative_field: ""
helpx_description: Sampler > Scripting and Development > Create a Plugin with Python and QML
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: PythonとQMLでプラグインを作成する
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '729'
ht-degree: 0%

---


# PythonとQMLでプラグインを作成する

このガイドでは、PythonとQMLを使用して簡単な自動保存プラグインを作成する方法について説明します。

## プラグイン構造

Samplerプラグインを読み込むには、少なくともPythonファイルとQMLファイルが必要ですが、プラグインパネルのアイコンに使用する画像など、他のファイルを含めることもできます。 次の例では、3つのファイルがあります。

* **autosave.py**&#x200B;には、プラグインのロジックが含まれており、その仕組みを決定します。
* **autosave.qml**&#x200B;は、Samplerのプラグインの外観を定義します。
* **autosave.svg**&#x200B;は、プラグインのアイコンとして使用されるベクターグラフィックです。

プラグインに必要なファイルを1つのフォルダーにまとめたら、編集/環境設定/プラグインとスクリプトを使用して、プラグインをSamplerに追加できます。 プラグインの管理の詳細については、[ここ](manage-installed-plugins-and-scripts.md)を参照してください。

## Python

次のコードは、自動保存プラグイン用の完全なPythonファイルです。 以下に、コードの内容を簡単に説明します。コードには、詳細情報を含むコメントも含まれています。

1. 関連するモジュールをインポートします。
   1. QtはマルチプラットフォームGUIツールキットです。 QtcCore、QtQml、およびQtQuickは、autosave.pyとautosave.qmlの間で通信するために使用するモジュールです。
1. プロジェクトをX分ごとに保存するメソッド&#x200B;**save()**&#x200B;を定義します。
1. 自動保存クラスを作成します。 このクラスは、**save()**&#x200B;メソッドがプラグインUIに接続する方法を指定し、パラメーターがプラグインの動作を変更できるようにします
1. プラグインのセットアップを実行するメソッド&#x200B;**register\_qml\_type()**&#x200B;を定義します。
1. Sampler内からプラグインを呼び出します。

### 自動保存.py

```
## Import QT & QML modules to create the UI

from PySide2 import QtCore, QtQml, QtQuick 

## Import Sampler API

import substance_sampler as ssa 

## Import other modules for this specific example

import datetime 

import os 

import threading 

 

 

## Save the project every X minutes

def save(interval): 

    global t 

    ssa.save_project() 

    if ssa.save_project(): 

        now = datetime.datetime.now() 

        print("Autosave: %d:%d:%d" % (now.hour, now.minute, now.second)) 

    t = threading.Timer(interval, save, [interval]) 

    t.start() 

 

 

t = None 

 

 

## Declare the API AutoSave

class AutoSave(QtQuick.QQuickItem): 

    def __init__(self, parent=None): 

        super(AutoSave, self).__init__(parent) 

 

## Declare a first API function

## This function can be called from the QML file

## with 2 arguments, one string and one integer

    @QtCore.Slot(str, int) 

    def start_auto_save(self, default_path, interval): 

        if not ssa.save_project(): 

            ssa.save_project_as(os.path.join(default_path, "autosave.ssa")) 

        global t 

        t = threading.Timer(10, save, [interval]) 

        t.start() 

        print("Launch Autosave") 

 

## Second function of the API

## With no argument

    @QtCore.Slot(None) 

    def stop_auto_save(self): 

        global t 

        t.cancel() 

        print("Stop Autosave") 

 

 

## Function to declare the API and the panel

## First argument is Python class of your API

## Second argument is name of the API you will use in the QML file

## Third and fourth is the API version. In this case, 1.0

## Last is the name of the panel in Sampler UI

def register_qml_type(): 

    QtQml.qmlRegisterType(AutoSave, "AutoSave", 1, 0, "AutoSave") 

 

 

## Execute the plugin in Sampler UI thread

ssa.run_in_main_thread(register_qml_type)
```


## QML

QMLファイルはプラグインのUIを定義します。 QMLはQt Markup Languageの略で、HTMLやXMLなどの他のマークアップ言語と同様に動作します。 [QMLについて詳しくは、こちらをご覧ください](https://doc.qt.io/qt-6/qmlapplications.html#:~:text=QML%20is%20a%20user%20interface%20specification%20and%20programming,imperative%20JavaScript%20expressions%20combined%20with%20dynamic%20property%20bindings。)。

autosave.qmlの一般的な構造は次のとおりです。

1. モジュールをインポートします。
   1. 読み込まれたQtモジュールは、ファイルで使用されているUI要素に必要です。
   1. **autosave.py**&#x200B;で作成されたAutosave APIクラスもインポートされます。 QMLファイルは20行目でこのクラスを参照しています。
1. 追跡が必要な変数を作成します。
   1. **autoSaveFolder**&#x200B;は、Samplerファイルの自動保存先フォルダーです。
   1. **timing**&#x200B;は、自動保存の間隔（秒単位）です。
   1. **textColor**&#x200B;を使用すると、プラグインUIのテキストの色を1か所で更新できます。
1. Python APIのインスタンス化
1. UIを定義します。
   1. これには、**autosave.py**&#x200B;で作成されたPython APIへのフックが含まれます。 以下に例を示します。
      1. 47行目では、「自動保存の間隔（分）:」要素が変更されるたびに、QMLファイル内の&#x200B;**タイミング**&#x200B;変数値が更新されます。
      1. 行64はAPIから&#x200B;**start\_auto\_save**&#x200B;関数を呼び出し、**timing**&#x200B;および&#x200B;**autoSaveFolder**&#x200B;変数をパラメーターとして渡します。
1. デフォルトのファイルパスをクリーンアップするメソッドを作成します。

### 自動保存.qml

```
/* 

Import Qt modules to design the UI 

https://doc.qt.io/qt-5/qtqml-syntax-basics.html 

*/ 

import QtQuick 2.15 

import QtQuick.Controls 2.15 

import Qt.labs.platform 1.1 

import AutoSave 1.0 // Import API defined in the Python file 

 

Rectangle { 

  id: root 

  anchors.fill: parent 

  color: "#333333" 

 

  property var autoSaveFolder: removeQmlFilePathPrefix(StandardPaths.writableLocation(StandardPaths.DocumentsLocation)) 

  property var timing: 300 

  property var textColor: "#b3b3b3" 

 

  AutoSave { 

      id: api // Instantiate the Python API 

  } 

 

  Column { 

    id: controls 

    anchors.top: parent.top + 10 

    anchors.left: parent.left + 10 

    anchors.right: parent.right 

    width: parent.width 

    spacing: 20 

    leftPadding: 10 

    topPadding: 10 

 

    Column { 

        spacing: 5 

        Text { 

            id: timingTitle 

            text: "Autosave every (min): " 

            color: root.textColor 

        } 

        SpinBox { 

            id: timingControl 

            from: 1 

            to: 10 

            stepSize: 1 

            value: 5 

 

            onValueModified: ()=>{ 

                root.timing = timingControl.value * 60 

            } 

        } 

    } 

    Row { 

        Text { 

            text: "Off" 

            color: root.textColor 

            anchors.verticalCenter: toggle.verticalCenter 

        } 

        Switch { 

            id: toggle 

            checked: false 

 

            onClicked: ()=>{ 

                if (checked === true) { 

                    api.start_auto_save(root.autoSaveFolder, root.timing) // Call a function of the API with 2 arguments 

                } 

                else if (checked === false) { 

                    api.stop_auto_save() // Call a function of the API 

                } 

            } 

        } 

        Text { 

            text: "On" 

            color: root.textColor 

            anchors.verticalCenter: toggle.verticalCenter 

        } 

 

    } 

    Column { 

        spacing: 5 

        Text { 

            text: "Default Autosave Path" 

            color: root.textColor 

            } 

        Row { 

            id: folderInput 

            TextField { 

                id: folderText 

                text: root.autoSaveFolder 

                readOnly: true 

            } 

            Button { 

                id: folderSelection 

                text: qsTr("...") 

                width: 40 

                onClicked: ()=>{ 

                    folderDialog.open() 

                    } 

            } 

        } 

    } 

 

    FolderDialog { 

        id: folderDialog 

 

        onAccepted: ()=>{ 

            root.autoSaveFolder = removeQmlFilePathPrefix(folderDialog.currentFolder) 

        } 

    } 

 

  } 

      function qmlFilePathPrefix() { 

        if (Qt.platform.os === "windows") { 

            return "file:///" 

        } 

        return "file://" 

    } 

    function removeQmlFilePathPrefix(filePath) { 

        var prefix = qmlFilePathPrefix() 

        return filePath.toString().replace(prefix, '') 

    } 

}
```


## SVG

**autosave.svg**&#x200B;が明示的に呼び出されていない、または&#x200B;**autosave.py**&#x200B;または&#x200B;**autosave.qml**&#x200B;で言及されていない可能性があります。 これは、SamplerがPYファイルと同じ名前のSVGファイルを検索し、自動的にプラグインアイコンとして使用するためです。

>[!NOTE]
>
> プラグインフォルダーに、プラグインのPYファイルと一致しないファイル名のSVGが含まれている場合、プラグインにはアイコンが含まれません。 これにより、プラグインがSampler UIに表示されない現象が発生する可能性があります。 この場合は、Samplerの右のバーにカーソルを合わせて、プラグインをハイライト表示します。
> 
> お使いのブラウザーは、HTML 5のビデオ要素をサポートしていません

プラグインフォルダーにプラグインファイルが含まれていない場合は、デフォルトのSVGアイコンが代わりに使用されます。

以下に、上記で作成した自動保存プラグインで使用できるSVGの例を示します。

[autosave.svg](https://helpx.adobe.com/content/dam/help/en/substance-3d/documentation/sadoc/files/234455541/234455542/1/1662460696349/autosave.svg)

## 自動保存プラグインの制限

上記で作成した自動保存プラグインは機能しますが、完全ではありません。 例えば、自動保存を有効にした後に自動保存の間隔を調整しても、自動保存の間隔の時間は実際には変更されません。UIの値をAPIに送信するには、自動保存を無効にしてから再度有効にする必要があります。

PythonとQMLを一緒に使い始めたばかりの方は、このバグを修正すると、プラグインの異なる部分がどのように通信しているかを理解するのに役立ちます。
