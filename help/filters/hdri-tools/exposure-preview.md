---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/filters/hdri-tools/exposure-preview.html"
breadcrumb-title: ''
description: Substance 3D Samplerの露光量プレビューツールを使用して、変更を適用する前にHDRI画像の露光量調整をプレビューします。
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Exposure Preview
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 露光量プレビュー
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '239'
ht-degree: 0%

---


# 露光量プレビュー

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-exposurepreview-18-n-d.png)

**イン：** HDRI ツール

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 説明

**露光量プレビュー** **フィルター**&#x200B;を使用すると、一連の露光量をすばやくプレビューできます。

**露光量プレビューフィルター**&#x200B;の機能を以下で確認できます。

![](../../assets/3d-2d-filters-cropped-0029-exposure-preview-in.jpg)

上の画像では、環境光が作成され、HDR画像データが&#x200B;**2Dビュー**&#x200B;に表示されています。

![](../../assets/filters-cropped-0028-exposure-preview-out.jpg)

レイヤースタックに&#x200B;**露光量プレビュー** **フィルター**&#x200B;を追加すると、様々な露光量で環境光を表示する新しいチャンネル（環境診断）が使用できるようになります。

</td>
</tr>
</table>

## パラメーター

**基本パラメーター**

* **最小露出(EV)**: -8 ～ 8\
  露光量が最も少ない画像の露光量を設定します。
* **最大露光量(EV)**: -8 ～ 8\
  最も露光量の多い画像の露光量を設定します。

## 使用方法ガイド

**露光量プレビューフィルター**&#x200B;は、他のSamplerフィルターとは少し動作が異なります。 このツールは、環境光に適した露光量を見つけやすくすることを目的としていますが、実際には環境チャンネルには影響しません。代わりに、**露光量プレビューフィルター**&#x200B;をレイヤースタックに追加すると、追加のチャンネルが&#x200B;**2Dビュー** （環境診断チャンネル）に表示できるようになります。

環境診断チャンネルを表示すると、様々な露光量値で2D環境イメージの複数のインスタンスを確認できます。 **露光量プレビューフィルター**&#x200B;のパラメーターを調整して、環境診断チャンネルに表示される露光量の範囲を変更します。
