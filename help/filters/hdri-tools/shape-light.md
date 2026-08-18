---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/hdri-tools/shape-light.html"
breadcrumb-title: ''
description: Substance 3D Samplerのシェイプライトツールを使用して、カスタムシェイプの光源をHDRI環境に追加し、クリエイティブな照明を実現します。
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Shape Light
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: ライトを形成
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '264'
ht-degree: 0%

---


# ライトを形成

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-shapelight-18-n-d.png)

**イン：** HDRI ツール

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 説明

長方形または円盤状のライトを作成します。

</td>
</tr>
</table>

## パラメーター

**基本パラメーター**

* **図形のカラーモード**:\
  ライトのカラーの決定に使用する方法を選択します。 使用可能なパラメーターは、この選択に基づいて変更されます。
  * **温度（ケルビン）**
    * **温度**: 1000 ～ 27000\
      ライトの温度を調整します。
  * **RGB**
    * **色**：色の選択\
      ライトのカラーを選択します。
  * **画像の入力**
    * **シェイプ画像の入力**：画像/ブラシ\
      カラーとして使用する画像を読み込みます。 ブラシツールを使用して&#x200B;**2Dビュー**&#x200B;で直接ペイントすることもできますが、このフィルターでは予測できない結果が生じる可能性があります。
* **ホットスポットの露出(EV)**: 0 ～ 10\
  ホットスポットの露光量を調整します。 ホットスポットは、見にくくなったり不可能になったりします。新しい&#x200B;**シェイプライトフィルター**&#x200B;で、**シェイプの色温度**&#x200B;を1000に設定し、**ホットスポットの露出** **(EV)**&#x200B;を10に設定して、シェイプの中心にホットスポットを見るようにします。
* **図形**:\
  ライトのシェイプを設定します。

**位置**

* **ホットスポットの位置**: 0 ～ 1\
  ホットスポットの位置のオフセット
* **マトリックスのオフセット**: -2 ～ 2\
  シェイプのライトの位置を変更します。 **2Dビュー**&#x200B;でライトをドラッグして位置を変更することもできます。

**図形**

* **図形の露出(EV)**: 0 ～ 10\
  光の露光量の調整
* **図形の硬さ**: 0 ～ 1\
  光のエッジをソフトにする
* **ホットスポットのサイズ**: 0 ～ 1
* **ホットスポットフォールオフ**: 0 ～ 1\
  ホットスポットのエッジの柔らかさを調整します。

**背景**

* **バックグラウンドガンマ**:\
  背景ガンマの決定に使用するカラーシステムを選択します。
