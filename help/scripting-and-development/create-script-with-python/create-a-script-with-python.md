---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/scripting-and-development/create-a-script-with-python.html"
breadcrumb-title: ''
description: Substance 3D Sampler用のPythonスクリプトを作成してワークフローを自動化し、アプリケーション機能を拡張する方法について説明します。
helpx_creative_field: ""
helpx_description: Sampler > Scripting and Development > Create a Script with Python
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Pythonでスクリプトを作成する
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '189'
ht-degree: 0%

---


# Pythonでスクリプトを作成する

このガイドでは、Pythonで簡単な自動保存プラグインを作成する方法について説明します。

## スクリプト構造

スクリプトをSamplerに読み込むには、1つのPYファイルが必要です。 以下のスクリプト例をPYファイルとして保存し、Samplerに読み込むことができます。

## スクリプト例

以下のスクリプトでは、マテリアルの各レイヤーに新しいランダムシードを選択して、マテリアルのバリエーションを自動的に作成します。 これは、特定のランダムシードに依存するのではなく、マテリアルを一般的なケースで使用できるようにするのに便利です。

### random\_seed\_variations.py

```
import substance_sampler as ssa 

from random import randrange 

 

## Get the current asset loaded in the layer stack

my_asset = ssa.get_selected_asset() 

 

## Create a list of all layers of the current asset

my_asset_layers = my_asset.get_layers() 

 

## Go through the layers list

for layer in my_asset_layers: 

## Go through all parameters of each layer

    for parameter in layer.parameters: 

## if the parameter is Random Seed, change is value

        if parameter.label == "$randomseed": 

            parameter.value = randrange(10000) 

            print(f"Random Seed for layer {layer.name}: {parameter.value}") 

 
```


上記のコードには、各行で何が起こっているかを説明するコメントが含まれています。

## スクリプトの読み込み

上記のスクリプトをPYファイルとしてコンピューターに保存したら、編集/環境設定/プラグインとスクリプトを使用して読み込むことができます。 読み込みが完了すると、**スクリプト**&#x200B;オプションが&#x200B;**ファイル**&#x200B;と&#x200B;**編集**&#x200B;と一緒にメニューバーに表示されます。 ここからスクリプトを実行できます。

スクリプトの管理について詳しくは、[こちら](../manage-installed-plugins-and-scripts.md)を参照してください。
