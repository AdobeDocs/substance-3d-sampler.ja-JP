---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/pipeline-and-integrations/substance-connector.html"
breadcrumb-title: ''
description: Substance 3D SamplerでSubstanceのSend-to機能を使用し、コネクター経由で他のアプリケーションに直接アセットを送信する方法について説明します。
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Substance送信先
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '302'
ht-degree: 0%

---


# 任意のアプリに送信

4.5 Samplerリリースから、コネクタが実装されている任意のアプリにSamplerからアセットを直接送信できるようになりました。\
これにより、Samplerからサードパーティ製品にアセットをワンクリックで送ることができるため、手動で書き出しや読み込みを行う必要がなくなり、時間を節約できます。

現在、Send-toはBlender、Unreal Engine、Unity、3ds Max、MayaでSubstanceプラグインを通じて使用できます。

## サポート対象アプリのバージョン

Send-toを使用するには、Sampler、サードパーティアプリケーション、プラグインの正しいバージョンが必要です。

Send-toを使用するために必要な最小バージョンは次のとおりです。

* <b>アンリアルエンジンプラグイン</b>
  * UE5.4以降はすべて完全にサポートされています。
  * *UEマーケットプレイスで公開*

* <b>Mayaプラグインv3.0.0+</b>
  * Maya 2025、2024、2023、2022でサポートされています。
  * *Maya 2025以降で利用可能ですぐに利用できます。以前のバージョンでは、プラグインを[webサイト](https://www.adobe.com/products/substance3d/plugins/substance-in-maya.html "Maya WebページのSubstance")*&#x200B;からダウンロードする必要があります。

* <b>3ds Maxプラグインv3.0.0+</b>
  * 3ds Max 2025、2024、2023、2022でサポートされています
  * *3ds Max 2025以降は既定で利用可能。以前のバージョンのプラグインは[webサイト](https://www.adobe.com/products/substance3d/plugins/substance-in-3ds-max.html "3ds Max WebページのSubstance")*&#x200B;からダウンロードする必要があります

* <b>Unityプラグインv3.11+</b>
  * Unityバージョン2022、2021または2020
  * *プラグインをアセットストアからダウンロードする必要があります*

* <b>Blenderプラグインv2.1+</b>
  * Blenderバージョン3.0以降
  * *プラグインは[Webサイト](https://www.adobe.com/products/substance3d/plugins/substance-in-blender.html "Blender WebページのSubstance")*&#x200B;でダウンロードできます
