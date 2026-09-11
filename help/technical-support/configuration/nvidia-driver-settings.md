---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/technical-support/configuration/nvidia-driver-settings.html"
breadcrumb-title: ''
description: Substance 3D SamplerのNVIDIAドライバーを設定して、GPUパフォーマンスを最適化し、動作の遅れを解決する方法について説明します。
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Configuration > NVIDIA Driver Settings
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: NVIDIAドライバー設定
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '262'
ht-degree: 0%

---


# NVIDIAドライバー設定

NVIDIA GPUを使用していて、パフォーマンスが低下する場合、一般的な原因は2つあります。

1. ドライバが見つからないか、最新ではありません
1. Samplerが正しくないGPUを使用しています

## ドライバーの更新

NVIDIAドライバーを更新するには：

1. NVIDIAのドライバーのダウンロードページに移動します – <https://www.nvidia.com/Download/index.aspx?lang=en-us>
1. GPUモデルを選択し、ドライバーをダウンロードします。
1. ダウンロードしたファイルでドライバーをインストールします。

最新のドライバーがインストールされたら、Samplerを開いてパフォーマンスが改善されたかどうかを確認します。 パフォーマンスが低下する場合は、Samplerが正しくないGPUを使用している可能性があります。

## Samplerの設定

Samplerで使用されているGPUを確認するには、次の手順を実行します。

![](../../assets/nvidiacontrolpanel.png)

1. NVIDIAコントロールパネルを開きます。 NVIDIAコントロールパネルを開くには、次のいずれかの操作を行います。
   1. スタートメニューを使用してNVIDIAコントロールパネルを検索します。
   1. システムトレイで、Geforceアイコンを右クリックし、「NVIDIAコントロールパネル」を選択します。
1. NVIDIAコントロールパネルの左側のメニューで、「 3D設定の管理」を選択します。
1. 「プログラム設定」タブを選択します。
1. 「カスタマイズするプログラムを選択」のドロップダウンを使用して、Samplerを見つけます。
1. Samplerがドロップダウンに表示されない場合は、「追加」を使用します。
   1. Samplerのインストール場所を参照します（デフォルトのインストール場所は&#x200B;**C:/Program Files/Adobe/Adobe Substance 3D Sampler**&#x200B;です）。
   1. インストール場所から&#x200B;**Adobe Substance 3D Sampler.exe**&#x200B;を選択してください。
1. Samplerを選択した状態で、「Select the preferred graphics processor for this program:」の下で「High Performance NVIDIA Processor」を選択します。
1. 「適用」をクリックします。

このプロセスに従ったら、Samplerを開いてパフォーマンスが改善されたかどうかを確認します。
