---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/technical-support/technical-issues/stability-issues/crash-when-exporting-a-material.html"
breadcrumb-title: ''
description: VRAMまたはGPUのメモリ不足が原因で発生したマテリアルをSubstance 3D Samplerで書き出すときに発生するクラッシュを修正する方法について説明します。
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Technical Issues > Stability issues > Crash when exporting a material
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: マテリアルの書き出し時のクラッシュ
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '89'
ht-degree: 0%

---


# マテリアルの書き出し時のクラッシュ

Samplerで作成したマテリアルを書き出すと、書き出し時にクラッシュすることがある。 このクラッシュは通常、書き出しプロセスの開始時にGPUで利用できるVRAMが不足していることが原因です（特にdelighterフィルターを使用したマテリアルの場合）。

書き出しの解像度を下げて他のアプリケーションを閉じると、メモリを解放して書き出しを完了させるのに役立つ場合があります。
