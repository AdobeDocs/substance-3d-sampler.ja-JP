---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/technical-support/technical-issues/stability-issues/crash-when-using-the-image-to-material-or-delighter.html"
breadcrumb-title: ''
description: VRAMが不十分であるために、Substance 3D Samplerで「画像をマテリアルに合わせる」フィルターまたは「明るくする」フィルターを使用する際に発生するクラッシュを修正する方法について説明します。
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Technical Issues > Stability issues > Crash when using the Image to Material or Delighter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 画像をマテリアルまたはハイライトに使用するとクラッシュが発生する
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '93'
ht-degree: 0%

---


# 画像をマテリアルまたはハイライトに使用するとクラッシュが発生する

**画像からマテリアル （AI搭載）**&#x200B;および&#x200B;**明るさ**&#x200B;フィルターには、多くの使用可能なVRAM （少なくとも1GB）が必要です。

2 GBのVRAMしか使用できないGPUカードを使用し、2K/4K解像度で動作している場合、フィルターの実行に十分なメモリを割り当てられず、クラッシュが発生する可能性があります。
