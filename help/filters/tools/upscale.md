---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/filters/tools/upscale.html"
breadcrumb-title: ''
description: Substance 3D Samplerのアップスケールツールを使用すると、AIを活用したアップスケールテクノロジーにより、テクスチャ解像度を上げることができます。
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: アップスケール
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '198'
ht-degree: 2%

---


# アップスケール

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![フィルターアイコン](../../assets/SAPR_SuperResolution_18_N_D.png)

**イン：**&#x200B;ツール

</td>
<td style="border: 0;" valign="top">

## 説明

<b>アップスケール</b>フィルターは、AIを使用して、PBRチャンネル（ベースカラー、粗さ、標準、メタリック、Height）をその下のレイヤーからアップサンプリングします。

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">



</td>
<td style="border: 0;" valign="top">

![](../../assets/F5W_vAHaYAQLsz7.jpg)

</td>
</tr>
</table>

この例では、1024 x 1024 pxの画像から始めますが、出力結果は4098 x 4098 pxになります。 <b>アップスケール</b>フィルターを使用した結果がより明確になりました。

</td>
<td style="border: 0;" valign="top">

>[!NOTE]
>
> **詳細フィルター**
> 
> <b>アップスケール</b>は高度なフィルターです。\
> この機能を最大容量で使用し、ぼやけた結果を回避するには、「レイヤー入力最大」または「レイヤー入力最小」で<b>アップスケール</b>以下のレイヤーを設定することをお勧めします。
> 
> 使用できる<b>アップスケール</b>フィルターの数に制限はありませんが、解像度が8Kを超えるアップサンプリングはパフォーマンスに大きな影響を与える可能性があります。

</td>
</tr>
</table>

## パラメーター

<b>基本パラメーター</b>

* <b>サンプルのアップ</b>:ボタングループの切り替え\
  アップスケールする乗算係数を選択します

## 方法

![](../../assets/SAPR_Upscale_screen_001.png)

上の画像では、低解像度の画像が[Image to Material (AI Powered)](image-to-material.md)によって処理されます。

![](../../assets/SAPR_Upscale_Screen_003.png)

<b>アップスケール</b>フィルターが追加され、結果のサンプルがアップされます。 素材の品質を保ったまま、より高い解像度に到達するためにディテールをハリキュートします。 プロパティでを選択して、2または4でアップサンプルできます。
