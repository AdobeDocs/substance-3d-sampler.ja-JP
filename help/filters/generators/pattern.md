---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/pattern.html"
breadcrumb-title: ''
description: Substance 3D Samplerのパターンジェネレーターを使用して、マテリアルテクスチャのプロシージャルパターンと反復デザインを作成します。
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Pattern
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: パターン
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '266'
ht-degree: 1%

---


# パターン

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-pattern-18-n-d.png)

**In:**&#x200B;ジェネレーター

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 説明

用意されているいずれかのオプションから素材にパターンを追加するか、画像またはブラシを使用して独自のパターンをカスタマイズします。

*デニムに適用された&#x200B;**パターンフィルター**&#x200B;の例。*

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0011-pattern-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0010-pattern-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## パラメーター

<b>基本パラメーター</b>

* <b>ランダムシード</b>: 0 ～ 1\
  ランダムシードは、このフィルターのランダム度を使用する他のパラメーターのランダム値を決定します。
* <b>パターン</b>：画像の選択および/またはペイント\
  テクスチャジェネレーターでパターンを選択するか読み込みます
* <b>カラーモードの選択</b>:マテリアルまたはカラーのみ\
  <b>マテリアル</b>モードはすべての&#x200B;*PBRチャンネル*&#x200B;に影響し、<b>色のみ</b>モードはマテリアルの&#x200B;*BaseColor*&#x200B;にのみ影響します。
* <b>カラー適用量</b>: 1 ～ 10\
  パターンからアクティブなカラーの量を選択します
* <b>色相</b>: 0 ～ 1\
  パターンの色相を調整する
* <b>マスクカラー</b> ：切り替え\
  選択した色をマスクします。<b>色量</b>に依存します
* <b>色の置換： </b>切り替え\
  選択した色を<b>色量</b>に応じて置き換える
* <b>粗さ</b> : 0 ～ 1\
  <b>色の量</b>に応じて、選択した色の粗さを設定
* <b>メタリック</b>: 0-1\
  <b>色の量</b>に応じて、選択した色の粗さを設定
* <b>エンボスモード</b>：切り替え\
  選択した色のエンボスの方向を選択します。<b>の色量</b>によって決まります
* <b>エンボス強度： </b>0-1<b>\
  </b>選択した色のエンボスの強さを調整します。調整は、<b>色の量</b>によって異なります。
* <b>エンボスの距離： </b>0-1\
  選択した色の浮き出し領域を引き伸ばして滑らかにします。適用量は<b>で決まります</b>
* <b>エンボス粒子： </b>0-1\
  <b>カラー適用量</b>に応じて、選択したカラーで粒子を追加します
