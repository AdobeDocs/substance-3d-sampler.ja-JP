---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/getting-started/export/managing-custom-presets.html"
breadcrumb-title: ''
description: ワークフローを最適化するためのSubstance Designerを使用して、Substance 3D Samplerでカスタム書き出しプリセットを作成および編集する方法について説明します。
helpx_creative_field: ""
helpx_description: Sampler > Getting Started > Export > Managing custom presets
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: カスタムプリセットの作成と編集
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '278'
ht-degree: 1%

---


# カスタムプリセットの作成と編集

カスタムプリセットは、Substance 3D Designerで作成できます。

カスタムプリセットの作成では、Samplerのカスタムフィルターの作成と同じ規則に従います。 ドキュメントは[こちら](../../filters/custom-filters.md)から入手できます。

## 作成

## グラフを作成する

Substance Designerを開き、新しいSubstanceグラフを作成します。

グラフのプロパティを開き、次の必須情報を入力します。

* ラベル： Samplerインターフェイスで使用するカスタムプリセットの名前を入力します。
* ユーザーデータ： <b>alchemist::type=filter</b>

## 入力および出力の定義

### 入力

入力値は、書き出しの前に変換するマテリアルチャンネルを表します。

マテリアルチャンネルごとに入力カラーノード（またはグレースケール）を作成し、各入力ノードの属性に<b>使用方法</b>を追加して、マテリアルとカスタムプリセットの間で接続が行われるようにします。

例：ベースカラー入力の定義

![](../../assets/custom-input.png){width="600px"}

### 出力

出力は、テクスチャ書き出しの結果を表します。

テクスチャごとに1つの出力ノードを作成し、各出力ノードの属性に<b>usage</b>と<b>label</b>を追加します。 <b>ラベル</b>は、エクスポータウィンドウのチャンネルリストとテクスチャファイルの名前に表示されます。

例：カスタムテクスチャのカラー不透明度の定義

![](../../assets/custom-output.png){width="600px"}

#### チャンネルパッキングとチャンネル変換の例

1つのRGBテクスチャに3つのグレースケールチャンネルをパッキング:

![](../../assets/channel-packing-example.png){width="600px"}

PBRメタリック/ラフネスからPBR Specular/光沢へのチャンネルの変換：

![](../../assets/channel-conversion.png){width="600px"}

## 読み込み

新しいプリセットを読み込むには：

1. <b>プリセットドロップダウン</b>の右側にある<b>プリセットの管理</b>ボタンをクリックします。
1. <b>プリセットリスト</b>の下部にある「<b>プリセットを読み込み</b>」ボタンを使用します。

![](../../assets/Managing-presets-Dropdown.png.img.png){width="400px"}
