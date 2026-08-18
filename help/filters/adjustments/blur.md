---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/filters/adjustments/blur.html"
breadcrumb-title: ''
description: Substance 3D Samplerのぼかしフィルターを使用して、ぼかし効果を適用し、テクスチャおよびマテリアルレイヤーでの画像のシャープさを軽減します。
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Blur
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: ぼかし
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '172'
ht-degree: 2%

---


# ぼかし

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-blur-18-n-d.png)

**内：**&#x200B;調整

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 説明

マテリアル全体をぼかすか、特定のチャンネルを選択してぼかします。

**ぼかしフィルター**&#x200B;の下の画像は、基本カラーチャンネルに適用されています。

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0055-blur-in.jpg)

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0054-blur-out.jpg)

</td>
</tr>
</table>

</td>
</tr>
</table>

## パラメーター

**基本パラメーター**

* **強度**: 0 ～ 1\
  すべてのチャンネルに適用されるぼかしの量を調整

**チャネルごとのカスタム**

これらのコントロールを使用して、各チャンネルのぼかしの量を個別に調整します。 まず、チャンネル固有のぼかしを有効にします。スライダーが表示され、そのチャンネルに適用されるぼかしの量を制御できます。

>[!NOTE]
>
> チャンネル固有のぼかしは、マテリアル全体の&#x200B;**基本パラメーター> Intensity**&#x200B;ぼかしを上書きします。 したがって、マテリアルのぼかし強度を1に設定し、チャンネルを有効にしてぼかし強度を0に設定した場合、チャンネルはまったくブラーされませんが、他のすべてのチャンネルはぼかされます。

* ***チャンネル*** **– カスタムぼかしの強さ**：切り替え\
  チャンネル固有のぼかし値を有効にします。
* ***チャンネル*** ***-*** **ぼかしの強さ**: 0 ～ 1\
  指定したチャンネルのぼかしを調整します。
