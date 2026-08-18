---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/filters/wear-and-finish/rust.html"
breadcrumb-title: ''
description: Substance 3D Samplerの錆フィルターを使用すると、金属の材質や表面にリアルな錆効果や腐食効果を与えることができます。
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Rust
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 錆
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '315'
ht-degree: 1%

---


# 錆

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-rust-18-n-d.png)

**イン：**&#x200B;摩耗と仕上げ

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 説明

**錆フィルター**&#x200B;を使用して、酸化金属の層を素材に加えます。

**錆フィルター**&#x200B;を適用する前と後の金属の素材を以下の画像で確認できます。

![](../../assets/3d-filters-cropped-0002-rust-out.jpg){width="200px"}

</td>
</tr>
</table>

## パラメーター

**基本パラメーター**

* **ランダムシード**:\
  ランダムシードは、このフィルターのランダム度を使用する他のパラメーターのランダム値を決定します。
* **錆スプレッド**: 0 ～ 1\
  錆の広がりと量をコントロールします。
* **エッジの影響**: 0 ～ 1\
  曲線マップに基づいて、錆とエッジの相互作用を調整します。
* **スプレッドSmoothness**: 0 ～ 1\
  この値を大きくすると、錆びた領域がぼやけて見え、小さくすると、ディテールが際立ちます。
* **金属のみに影響**：切り替え\
  有効にすると、**錆フィルター**&#x200B;は、メタリック値が0より大きい領域にのみ影響します。

**錆**

* **錆の図形**:\
  錆の基になるパターンを変更します。
* **錆の強さ**: 0 ～ 1\
  錆効果の強度を調整します。 この値を大きくすると、錆が古く強く見えます。

**ピール**

* **ピールスケール**: 0 ～ 1\
  剥離錆のスケールを変更します。
* **標準のピール強度**: 0 ～ 1\
  ピールの法線の可視性を調整します。
* **ピールHeightの強さ**: 0 ～ 1\
  Heightマップ上でのピーリングの影響を調整します。

**滴る**

* **滴の強さ**: 0 ～ 1\
  ドリップ効果の強さを変更します。
* **ドリップの方向**: 0 ～ 1\
  重力や風に合わせて、しずくの向きを調整します。
* **滴の長さ**: 0 ～ 1\
  ソースからどの程度滴り出すかを調整します。

**マスク**

* **マスクを使用**：切り替え\
  カスタムマスクの使用を有効または無効にします。 有効にすると、次のパラメーターが表示されます。
  * **マスク**：画像/ブラシ\
    マスクとして使用する画像を選択するか、ブラシを使用して2Dビューでカスタムマスクを直接ペイントします。
  * **カスタムマスク – ぼかし**: 0-1\
    マスクをぼかします。
  * **カスタムマスク – 反転**：切り替え\
    マスクを反転します。
