---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/cracks.html"
breadcrumb-title: ''
description: Substance 3D Samplerの亀裂フィルターを使用して、リアルな亀裂パターンと地表損傷効果を素材に加えることができます。
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Cracks
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 亀裂
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '299'
ht-degree: 1%

---


# 亀裂

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-cracks-18-n-d.png)

**イン：**&#x200B;摩耗と仕上げ

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 説明

**亀裂フィルター**&#x200B;を使用すると、亀裂と隙間のネットワークを素材に加えることで、素材にエイジングやダメージを与えることができます。

**亀裂フィルター**&#x200B;は、すっきりとした大理石のマテリアルに適用されます。

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0043-cracks-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0042-cracks-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## パラメーター

**基本パラメーター**

* **ランダムシード**:\
  ランダムシードは、このフィルターのランダム度を使用する他のパラメーターのランダム値を決定します。
* **亀裂スプレッド**: 0 ～ 1\
  亀裂の広がりの範囲を調整します。これにより、クラックの幅と長さの両方が変更されます。
* **亀裂金額**: 0 ～ 1\
  表示する亀裂の数を変更します。

**マスク**

* **カスタムマスクを使用**：切り替え\
  カスタムマスクの使用を有効または無効にします。 有効にすると、次のパラメーターが表示されます。
  * **マスク**：画像/ブラシ\
    マスクとして使用する画像を選択するか、ブラシを使用して2Dビューでカスタムマスクを直接ペイントします。
  * **カスタムマスク – 反転**：切り替え\
    マスクを反転します。

**亀裂**

* **亀裂の色**:カラー選択\
  亀裂で表される内部サーフェスの色を変更します。
* **亀裂の粗さ** : 0 ～ 1\
  亀裂の粗さの値を調整します。
* **亀裂の粗さの不透明度** : 0 ～ 1\
  **亀裂の粗さ**&#x200B;の値が粗さマップに与える影響を調整します
* **亀裂メタリック**: 0 ～ 1\
  亀裂のメタリック値を変更します。
* **亀裂のメタリックの不透明度**: 0 ～ 1\
  **亀裂のメタリック**&#x200B;の値がメタリックマップに与える影響を調整します
* **Heightの適用度**: 0 ～ 1\
  亀裂の深度を調整します。 これは、フィルターのHeightマップと通常マップの結果の両方に影響します。

**詳細パラメーター**

* **法線の強度**: 0 ～ 1\
  クラックの法線の強度を調整します。
* **Height範囲**: 0 ～ 1\
  マテリアル全体のHeight範囲を修正します。 亀裂のHeightを調整するには、**亀裂/亀裂Heightの適用度**&#x200B;を使用します。
* **Heightの位置**: 0 ～ 1\
  マテリアル全体のHeightマップをオフセットします。
