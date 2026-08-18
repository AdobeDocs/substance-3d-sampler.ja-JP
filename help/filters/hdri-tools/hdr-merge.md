---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/hdri-tools/hdr-merge.html"
breadcrumb-title: ''
description: Substance 3D SamplerのHDR結合ツールを使用して、複数のハイダイナミックレンジ画像を1つの露光画像に結合します。
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > HDR Merge
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: HDR 結合
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '249'
ht-degree: 2%

---


# HDR 結合

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/S_HDRMerge_18_N_D.png)

**イン：** HDRI ツール

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 説明

**HDRマージ** **フィルター**&#x200B;を使用すると、SDR （標準ダイナミックレンジ）画像のコレクションをマージしてHDR画像を作成できます。

次の画像は、**HDRマージ**&#x200B;の結果を示しています。

![](../../assets/3d-2d-filters-cropped-0027-hdr-merge-in.jpg)

**HDR結合**&#x200B;を実行する前に、**3Dビュー**&#x200B;の球体はデフォルトの環境光を反映しています。 **2Dビュー**&#x200B;には、最初のスキャンイメージのインポートされたイメージデータが既定で表示されます。この場合、最も露出の低いイメージです。

![](../../assets/3d-2d-filters-cropped-0026-hdr-merge-out.jpg)

**HDRマージ** **フィルター**&#x200B;を追加すると、球体に新しい環境光（入力画像から生成されたHDR画像）が反射されます。

</td>
</tr>
</table>

## TParameters

**基本パラメーター**

* **入力露出デルタ(EV)**: 0-2\
  最高露光量と最低露光量の露出差を設定します。 露光量デルタが大きいと、マージ操作の結果のコントラストが大きくなります。
* **出力の自動露光量**：切り替え\
  自動露光量調整を有効または無効にします。
* **出力の露出オフセット(EV)**: -5 ～ 5\
  露光量をオフセットします。

## 使用方法ガイド

**HDR結合フィルター**&#x200B;と、SDR画像をHDR環境光に変換するのに役立つ他のフィルターの使用方法については、こちらを参照してください。

**HDRマージ** **フィルター**&#x200B;を使用するための基本的な手順は次のとおりです：

1. レイヤースタックに結合する画像のセットを読み込みます。
1. **HDR結合フィルター**&#x200B;をレイヤースタックに追加します。
1. 露光量の値が正しいことを確認するためにパラメーターを変更します。
