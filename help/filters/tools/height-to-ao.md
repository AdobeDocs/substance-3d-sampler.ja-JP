---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/height-to-ao.html"
breadcrumb-title: ''
description: Substance 3D SamplerのHeightからAOツールを使用して、マテリアルを作成するために高さマップをambient occlusionマップに変換します。
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Height to AO
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: AOのHeight
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '184'
ht-degree: 1%

---


# AOのHeight

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-hbao-18-n-d.png)

**イン：**&#x200B;ツール

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 説明

Heightと通常のデータからAmbient occlusionマップを生成します。

**AOフィルターへのHeight**&#x200B;の結果は、次の画像をご覧ください。

![](../../assets/3d-2d-filters-cropped-0025-height-to-ao-in.jpg)

上の図では、**2D ビュー**&#x200B;に高さマップが表示されています。 マテリアルには、この画像のAmbient occlusion情報が含まれていません。

![](../../assets/3d-2d-filters-cropped-0024-height-to-ao-out.jpg)

この画像では、Ambient occlusionマップは&#x200B;**AOフィルターへのHeight**&#x200B;によって作成されており、**2D ビュー**&#x200B;に表示されます。 一般に、Ambient occlusionは微妙な影響を与えるので、このマテリアルではあまり確認できません。マテリアルで&#x200B;**AOにHeight**&#x200B;フィルターを使用して、AOの適用度を上げ、Ambient occlusionを操作する感覚を得てください。

</td>
</tr>
</table>

## パラメーター

**基本パラメーター**

* **モード**:\
  Heightチャンネルからデータを生成するか、通常チャンネルからデータを生成するか、両方のチャンネルからデータを生成するかを選択します。
* **周囲オクルージョン – 強度**: 0-1\
  生成されたAOデータの強さを調整します
* **Ambient occlusion – スプレッド**: 0 ～ 1\
  生成されたAOデータの半径を調整する
