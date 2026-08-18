---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/technical-support/configuration/retrieving-the-installation-path.html"
breadcrumb-title: ''
description: スクリプト作成や設定用に、異なるプラットフォーム上のSubstance 3D Samplerのインストールパスを取得する方法について説明します。
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Configuration > Retrieving the installation path
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: インストールパスの取得
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 6%

---


# インストールパスの取得

このページでは、バージョンおよびプラットフォームに応じてアプリケーションのインストールパスを取得する方法に関する情報を再編成します。

## Windows

### Creative Cloud デスクトップ

1. Windowsレジストリエディター(**regedit**)を開きます。
1. レジストリキーに移動します： **&#x200B; HKEY\_LOCAL\_MACHINE\Software\Microsoft\Windows\CurrentVersion\App Paths\**
1. **Adobe Substance 3D Sampler.exe**&#x200B;というサブキーを開きます
1. キーの値には、インストールされているアプリケーションの実行可能ファイルへのパスが含まれています

>[!NOTE]
>
> このレジストリキーは、バージョン3以降でのみ使用できます。\
> 古いバージョンの場合、インストールパスは&#x200B;**HKEY\_CURRENT\_USER\Software\Microsoft\Windows\CurrentVersion\ Explorer\FileExts**&#x200B;のファイル関連付けから取得できます。

### Substance 3D Standalone

1. Windowsレジストリエディター(**regedit**)を開きます。
1. レジストリキー&#x200B;**HKEY\_LOCAL\_MACHINE\ SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall**&#x200B;に移動します
1. アプリケーションバージョンのAppIDに一致するサブキーを見つけます（以下の表を参照）
1. キーの値には、アプリケーションのインストール場所へのパスが含まれています

| バージョン | AppId |
| --- | --- |
| **1.x (2019.x)から2.x** | {B3506E85-E98F-4D48-A010-BE4DEE27D108} |
| **3.x （またはそれ以降）** | {ED4A4ABC-9B7D-44B8-984A-C8A994B69CFD} |

### スチーム

アプリケーションは、Steamインストールフォルダーの&#x200B;**steamapps/common/**&#x200B;サブフォルダーにインストールされます。

## Mac

Macでは、アプリケーションは次の場所にインストールされます。

| バージョン | パス |
| --- | --- |
| **3.x以降** | **/Applications/Adobe Substance 3D Sampler.app** |
| **レガシ** | **/Applications/Substance Alchemist.app** |

## Linux

Linuxでは、rpmパッケージは次のパスにインストールされています。

| バージョン | パス |
| --- | --- |
| **3.x以降** | **/opt/Adobe/Adobe\_Substance\_3D\_Sampler** |
| **レガシ** | **/opt/Allegorithmic/Substance\_Alchemist** |
