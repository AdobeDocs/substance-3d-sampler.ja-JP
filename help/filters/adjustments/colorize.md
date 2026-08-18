---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/adjustments/colorize.html"
breadcrumb-title: ''
description: Substance 3D Samplerのカラー化フィルターを使用して、テクスチャとマテリアルに色合いとモノクロのカラー化効果を適用します。
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Colorize
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 彩色
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '313'
ht-degree: 1%

---


# 彩色

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/S_ColorFill_18_N_D.png)

**内：**&#x200B;調整

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 説明

カラー化を使用すると、ディテールを失うことなく、選択したチャンネルにカラーを追加できます。

>[!NOTE]
>
> カラー化フィルターでは通常のチャンネルを変更できますが、通常のチャンネルの動作とマテリアルへの影響について十分に理解していない限り、変更しないことをお勧めします。 これは、通常、特定の状況でのみ必要な高度な機能です。

これらの画像では、**色彩の統一フィルター**&#x200B;を使用してベースカラーを調整し、より豊かな木目の素材を作り出しています。

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0045-colorize-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0044-colorize-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## パラメーター

**基本パラメーター**

このセクションで使用可能なパラメーターは、**チャネルの選択**&#x200B;に基づいて変更されます。

* **チャンネルの選択**:\
  フィルターを適用するチャンネルを選択します。 選択したチャンネルを2Dビューで表示して、フィルターの結果を直接確認することをお勧めします。
  * ***基本色/放射オプション***
    * ***チャンネル名*** **– カラー**:カラー選択\
      チャンネルの色付けに使用するカラーを選択します
    * ***チャンネル名*** **– 輝度を維持**：切り替え\
      有効にすると、元のカラーの明度または輝度の値が維持されます
    * ***チャネル名*** **– 強度**: 0-1\
      「カラー化」エフェクトの強度を調整します。
  * ***通常チャンネルのオプション***
    * **法線 – 勾配角度**: 0 ～ 90\
      法線のグラデーションを変更する
    * **法線 – 方向**: 0 ～ 360\
      法線の面の方向を調整
    * **通常 – 輝度を維持**：切り替え\
      有効にすると、元の法線からの輝度が維持されます
    * **法線 – 強度**: 0 ～ 1\
      「カラー化」エフェクトの強度を調整します。
* **カスタムマスク**:トグル\
  カスタムマスクの使用を有効または無効にします。 有効にすると、次のパラメーターが表示されます。
  * **マスク**：画像/ブラシ\
    マスクとして使用する画像を選択するか、ブラシを使用して2Dビューでカスタムマスクを直接ペイント
  * **カスタムマスク – ぼかし**: 0-1\
    マスクをぼかす
  * **カスタムマスク – 反転**：切り替え\
    マスクを反転
