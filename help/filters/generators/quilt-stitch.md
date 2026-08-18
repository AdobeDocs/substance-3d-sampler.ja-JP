---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/filters/generators/quilt-stitch.html"
breadcrumb-title: ''
description: Substance 3D Samplerのキルトステッチジェネレーターを使用して、マテリアルにキルトファブリックパターンとステッチテクスチャを作成します。
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Quilt Stitch
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: キルトステッチ
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '401'
ht-degree: 0%

---


# キルトステッチ

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-quiltstitch-18-n-d.png)

**In:**&#x200B;ジェネレーター

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 説明

このフィルターを使用して、素材にステッチしたキルトパターンをエミュレートします。

***キルトステッチフィルター**&#x200B;を適用する前と後*

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0005-quilt-stitch-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0004-quilt-stitch-out.jpg){width="200px"}

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
* **パターンの選択**:\
  ステッチ/キルトのパターンのスタイルを選択します
* **金額**: 1 ～ 5\
  パターンをタイリングする量をコントロールします
* **回転**:\
  パターンを回転
* **Topstitch**：切り替え\
  トップステッチの追加を有効にして、関連するパラメーターセクションを表示
* **縫い目**：切り替え\
  シームを追加し、関連するパラメータセクションを参照します。
* **キルト**：切り替え\
  キルトの追加を有効にして、関連するパラメータセクションを表示します。
* **エッジペイント**：切り替え\
  キルト化された断面の間のエッジをページングし、関連するパラメータ断面を確認します
* **詳細設定**：切り替え\
  **詳細**&#x200B;パラメーターを表示する

**Topstitch**

* **Topstitch Color**:カラー選択\
  トップステッチに使用する糸の色を設定します
* **Topstitchオフセット**: 0-1\
  キルティング領域のエッジからトップステッチをオフセット
* **Topstitch Rotation**: 0-1\
  トップステッチを構成するステッチの方向を変更する
* **Topstitchスケール**: 0-1\
  各寸法のトップステッチのサイズ（幅、長さ、Height）を調整します
* **穿刺強度**: 0 ～ 1\
  トップステッチによって生じたキルティングへのへこみを調整します
* **トップステッチの粗さ** : 0 ～ 1\
  スレッドの粗さを調整
* **Topstitch Metallic**: 0-1\
  ねじのメタリック値の調整

**縫い目**

* **縫い目** **選択範囲**:\
  使用する継ぎ目のスタイルを選択
* **縫い目の強度**: 0 ～ 1\
  継ぎ目の法線とHeightの強度を変更する
* **伸縮度**: 0 ～ 1\
  生地の伸縮が継ぎ目に与える影響の度合いを調整します。 この効果は非常にわずかです。

**キルト**

* **キルトの種類**:\
  使用するキルトスタイルを選択します
* **キルト強度**:\
  キルトエフェクトの法線強度とHeight強度を調整します

**エッジペイント**

* **エッジの選択**:\
  下にあるマテリアルの法線とHeightのディテールを痛みがオーバーライドするかどうかを選択します
* **エッジの色**:カラー選択\
  ペイントカラーを選択
* **エッジの粗さ** : 0 ～ 1
* **エッジのメタリック**: 0-1

**詳細**

* **Height**: 0 ～ 1\
  下にあるマテリアルからHeightマップの強度を調整
* **法線の強度**: 0 ～ 1\
  **キルトステッチ**&#x200B;フィルターによる法線マップの変更の強度を調整します。 これは、基礎となるマテリアルの法線には影響しません。
