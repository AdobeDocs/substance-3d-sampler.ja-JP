---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/filters/adjustments/hue-saturation.html"
breadcrumb-title: ''
description: テクスチャやマテリアルの色相、彩度、明度の値を調整するには、Substance 3D Samplerの色相・彩度フィルターを使用します。
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > HueSaturation
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 色相/彩度
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '216'
ht-degree: 0%

---


# 色相・彩度

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-hueandsat-18-n-d.png)

**内：**&#x200B;調整

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 説明

「色相・彩度」フィルターでは、ベースカラーおよび拡散チャンネルのカラーを調整できます。 また、マスクを使用して、画像の特定部分のカラーだけを変更することもできます。

下の画像は、タイルマテリアルの色相を調整するために使用される&#x200B;**色相/彩度フィルター**&#x200B;を示しています。

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0027-hue-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0026-hue-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## パラメーター

**基本パラメーター**

* **色相**: -1 ～ 1\
  画像の色相を調整します。これは、画像からマテリアルへのワークフローでカラーを補正するのに便利です。
* **彩度**: -1 ～ 1\
  彩度を調整してカラーを鮮やかにするか、カラーの適用度を下げます。
* **明度**: -1 ～ 1\
  カラーの明度を変更します。
* **色付け**：切り替え\
  無効にすると、フィルターによって既存のカラーが調整されます。 有効にすると、フィルターは、ディテールを維持しながら、色相、彩度、明度のスライダーに基づいてカラーを置き換えます。

**マスク**

* **カスタムマスクを使用**：切り替え\
  カスタムマスクの使用を有効または無効にします。 有効にすると、次のパラメーターが表示されます。
  * **マスク**：画像/ブラシ\
    マスクとして使用する画像を選択するか、ブラシを使用して2Dビューでカスタムマスクを直接ペイント
  * **カスタムマスク – ぼかし**: 0-1\
    マスクをぼかす
  * **カスタムマスク – 反転**：切り替え\
    マスクを反転
