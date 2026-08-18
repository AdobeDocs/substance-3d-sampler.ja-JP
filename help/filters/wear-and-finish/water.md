---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/water.html"
breadcrumb-title: ''
description: Substance 3D Samplerの水フィルターを使用して、マテリアルとテクスチャに水の効果、湿気、湿気を加えます。
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Water
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 水
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '357'
ht-degree: 0%

---


# 水

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-water-18-n-d.png)

**イン：**&#x200B;摩耗と仕上げ

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 説明

**浸食フィルター**&#x200B;を使用すると、素材の高い部分で磨耗します。

![](../../assets/water-compare.png)

</td>
</tr>
</table>

## パラメーター

**基本パラメーター**

* **ランダムシード**:\
  ランダムシードは、このフィルターのランダム度を使用する他のパラメーターのランダム値を決定します。
* **水位**: 0 ～ 1\
  水のHeightを調節しなさい。
* **水の暗さ**: 0 ～ 1\
  水を明るくまたは暗くします。
* **エッジの濡れ具合**: 0 ～ 1\
  マテリアルが濡れて見える水面からの距離を調整します。
* **水でのDirtを有効にする**：切り替え\
  粗さマップを少し修正して、水の上部にDirtを加えます。 **Dirtセクション**&#x200B;は、このパラメーターが有効な場合にのみ表示されます。
* **カスタムマスク**:トグル\
  有効にすると、次の追加コントロールが表示されます。
  * **マスク**：画像/ブラシ\
    カスタムマスクとして使用する画像を選択するか、ブラシを使用して&#x200B;**2Dビュー**&#x200B;で直接マスクをペイントします。

**Dirt**

このセクションは、**基本パラメーター/水のDirtを有効にする**&#x200B;が有効になっている場合にのみ表示されます

* **Dirt数量**: 0 ～ 1\
  水面に浮かぶDirtの量を調整します。
* **ゆがみの強さ**: 0 ～ 1\
  サーフェスDirtのゆがみ量を、水とマテリアルの残りの領域との交点に基づいて制御します。
* **Dirtの境界線の強さ**: 0 ～ 1\
  Dirtマスクの境界付近のサーフェスDirtの強度を管理します。
* **Dirtの境界線の距離**: 0 ～ 1\
  マテリアルの湿潤領域と乾燥領域の交点からのDirt境界の距離をコントロールします。
* **境界線の精度**: 0 ～ 1\
  Dirtの境界線の表示精度を調整します。
* **境界線ワープ**: 0 ～ 1\
  境界線をワープして、Dirtサーフェスの均一性を崩します。

**詳細パラメーター**

* **エッジの濡れ距離**: 0 ～ 1\
  エッジの濡れ性が乾燥した領域にどれくらい広がるかを制御します。
* **深度ぼかし量**: 0 ～ 1\
  水中にある領域のベースカラーをぼかす度合いを調整します。
* **深度ぼかしの不透明度**: 0 ～ 1\
  水の透明度を調整します。
* **スラッジの色**:カラー選択\
  水面の上にあるDirtのカラーを変更します。
* **スラッジの不透明度**: 0 ～ 1\
  スラッジの透明度を調整します。
