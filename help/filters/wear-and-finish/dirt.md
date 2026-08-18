---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/filters/wear-and-finish/dirt.html"
breadcrumb-title: ''
description: Substance 3D SamplerのDirtフィルターを使用して、マテリアルとテクスチャにリアルなDirtの重みと汚れの効果を加えます。
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Dirt
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 汚れ
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '289'
ht-degree: 1%

---


# 汚れ

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-dirt-18-n-d.png)

**イン：**&#x200B;摩耗と仕上げ

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 説明

**Dirtフィルター**&#x200B;を使用して、素材の上にDirtを加えます。 **Dirtフィルター**&#x200B;は、素材が古く、手入れがされていない印象を与えるのに最適です。

![](../../assets/dirt-filter-ceramic-mozaic-tiles-before-tra.png)

上の清潔なタイルと、下のタイルに適用されているDirtフィルターを比較します。

![](../../assets/dirt-filter-ceramic-mozaic-tiles-after-tra.png)

</td>
</tr>
</table>

## パラメーター

<b>基本パラメーター</b>

* <b>ランダムシード</b>: \
  ランダムシードは、このフィルターのランダム度を使用する他のパラメーターのランダム値を決定します。

* <b>Dirtスプレッド</b>: 0 ～ 1 \
  Dirtによってカバーされるサーフェス領域の範囲をコントロールします

* <b>上のDirtスプレッド</b>: 0 ～ 1\
  マテリアルの折り目に焦点を当てずに、Dirtで覆われる上面サーフェスをコントロールします

* <b>Dirtのコントラスト</b>: 0 ～ 1 \
  異なるDirtの領域の間のコントラストのレベルを調整して、Dirtと下になっているマテリアルのブレンド方法をコントロールします。

* <b>Dirtの不透明度</b>: 0 ～ 1 \
  ベースカラーチャンネルのDirtの透明度を制御します。 1は完全に不透明です。

* <b>Dirtの色</b>: 0 ～ 1 \
  Dirtのカラーを選択します。

* <b>Dirtの粗さ</b> : 0 ～ 1 \
  マテリアルのサーフェス全体の光の散乱を調整する

* <b>Dirtメタリック</b>: 0-1 \
  Dirtの表面の反射度を定義する

* <b>Height</b>: 0 ～ 1 \
  HeightマップへのDirtの影響を制御します

* <b>Dirtの標準強度</b>: 0 ～ 1 \
  Dirtレベルが法線マップに与える影響を制御します

* <b>表面の不完全性を使用</b>：切り替え \
  サーフェスの不完全性の使用を有効または無効にします。 有効にすると、追加のコントロールが表示されます。

  <b>表面の欠陥</b>：画像 \
  画像を読み込んで、表面の凹凸として使用するか、Samplerアセットライブラリのデフォルトで使用可能な「ステイン」や「Bnwスポット」などのテクスチャジェネレーターを使用します
