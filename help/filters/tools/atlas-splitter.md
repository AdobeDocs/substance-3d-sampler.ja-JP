---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/atlas-splitter.html"
breadcrumb-title: ''
description: Substance 3D SamplerのAtlas Splitterツールを使用して、テクスチャアトラスを個別のテクスチャマップに分割し、マテリアルの編集を行います。
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Atlas Splitter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Atlas Splitter
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '441'
ht-degree: 0%

---


# Atlas Splitter

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-atlassplitter-18-n-d.png)

**イン：**&#x200B;ツール

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 説明

**Atlas Splitter**&#x200B;は、アトラスの要素を整理して表示するのに便利なツールです。

下の画像は、**Atlas Splitter**&#x200B;の実際の動作を示しています。

![](../../assets/3d-2d-filters-cropped-0039-atlas-splittter-in.jpg)

上の画像は、レイヤースタックに追加されたアトラスマテリアルを示しています。 **Atlas Splitter**&#x200B;を使用して、アトラスから特定の要素を選択します。

![](../../assets/3d-2d-filters-cropped-0038-atlas-splitter-out.jpg)

レイヤースタックに&#x200B;**Atlas Splitter**&#x200B;が追加されると、1枚の葉や、アトラスマテリアルの他の要素に焦点を合わせることができます。

</td>
</tr>
</table>

## パラメーター

**基本パラメーター**

* **グリッドビュー**:トグル\
  グリッド表示と要素の個々の表示を切り替えます。 有効にすると、次の追加パラメーターが表示されます。
  * **グリッドの不透明度**: 0 ～ 1\
    グリッドの不透明度を変更する
  * **グリッド選択の不透明度**: 0 ～ 1\
    選択したエレメントの境界線の不透明度を変更
  * **自動スケール**：切り替え\
    各グリッドの正方形を塗りつぶすようにアトラス要素を拡大/縮小するかどうかを切り替えます。
* **自動切り抜き**：切り替え\
  選択したシェイプの切り抜きを調整するかどうかを選択します。 有効にすると、追加のオプションが表示されます。
  * **自動切り抜きモード**:\
    選択した要素を切り抜いてマテリアルのスペースいっぱいにする方法を選択します。
* **図形の選択**: 1 ～ 10\
  アトラスのどの要素を選択するかを変更します。 10個を超える要素を持つアトラスの場合、**図形の選択**&#x200B;の値に数値を入力して、スライダーの範囲を変更できます。
* **回転**: 0 ～ 1\
  要素の回転

**詳細パラメーター**

* **シェイプの許容値（小）**: 0 ～ 1\
  **Atlas Splitter**&#x200B;が選択する図形の最小サイズを調整します。 これは、ノイズを除外する場合に便利です
* **自動回転**：切り替え\
  有効にすると、エレメントは自動的に回転して同じ向きになります。
* **不透明度マスクを縮小**: 0 ～ 4\
  不透明度マスクのスケールを調整します。 この値を大きくすると、不透明マスクの質が低下する可能性があります。
* **図形の検出精度**:\
  使用するシェイプ検出アルゴリズムを選択します。
* **拡張幅**: 0-32\
  拡張を変更します。これにより、エレメントの境界線のカラーがマスクされた領域に押し出され、アトラスエレメントのエッジの透明度の問題を回避できます。 **2Dビュー**&#x200B;で基本カラーチャンネルを表示して、結果を確認します。
* **カスタム背景色**：切り替え\
  有効にすると、法線チャンネルの背景色を変更するコントロールが表示されます。
  * **標準の背景カラー**:カラー選択\
    マテリアルの透明な部分の法線チャンネルのカスタム背景色を選択します。
* **Heightの背景の色**: 0 ～ 1\
  Heightチャンネルの背景色を調整します。 一般に、Heightの背景をアトラス要素の境界線の平均Heightと一致させて、要素の境界線で斑点が生じないようにすることをお勧めします。
