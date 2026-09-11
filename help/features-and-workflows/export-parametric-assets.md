---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/features-and-workflows/export-parametric-assets.html"
breadcrumb-title: ''
description: Samplerからパラメトリックアセットを書き出し、Substance 3D Samplerに戻らずに他のアプリケーションでパラメーターを変更する方法について説明します。
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > Export parametric assets
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: パラメトリックアセットの書き出し
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '301'
ht-degree: 1%

---


# パラメトリックアセットの書き出し

表示されるパラメーターは、Samplerに戻らなくても、他のアプリケーションで変更できます。 これにより、反復時間が短縮され、アプリケーションを切り替えることなく、最適な外観を見つけることに集中できます。

## パラメーターの表示と公開解除

パラメーターを表示するには、**プロパティパネル**&#x200B;を開きます。 目的のパラメーターにカーソルを合わせるか右クリックし、パラメーターアイコンまたは「このピンーを表示」をクリックします。

![](../assets/ezgif-com-gif-maker-2.gif)

パラメーターの公開を解除するには、次の2つの方法があります。

* **表示されるパラーメーターパネル**&#x200B;で、パラメーターを右クリックし、「公開しない」を選択します。

  ![](../assets/ezgif-com-gif-maker-3.gif)
* **プロパティパネル**&#x200B;で、クロスされたピンのアイコンをクリックするか、パラメーターを右クリックして「このパラメーターを公開しない」を選択します。

  ![](../assets/ezgif-com-gif-maker-4.gif)

次のフィルターのパラメーターは表示できません：

* 画像からマテリアル (AI 搭載)
* コンテンツに応じた塗りつぶし
* Heightに垂直
* アップスケール

公開されたパラメーターを含むレイヤーの上にフィルターの1つを追加した場合、そのフィルターは書き出し時に公開されません。\
これを避けるには、フィルターを削除するか、表示されるパラメーターのあるレイヤーに影響を与えない場所に配置します。

ブレンドからパラメータを公開した場合、スタックの一番下のレイヤを移動すると、それらのパラメータは失われます。

![](../assets/ezgif-com-gif-maker-10.gif)

## パラメーターの編集

**表示されるパラーメーターパネル**&#x200B;でパラメーターのラベルを右クリックし、新しい名前を入力して「適用」をクリックします。

![](../assets/ezgif-com-gif-maker-5.gif)

![](../assets/ezgif-com-gif-maker-6.gif)

**表示されるパラーメーターパネル**&#x200B;のパラメーターは、**プロパティパネル**&#x200B;と同じように使用できます。

## マテリアルの書き出し

マテリアルを表示されるパラメーターと共に書き出すには

1. <b>書き出しパネルを開きます。</b>
1. 書き出しをクリックします。
1. SBSARまたはSBSを選択します。
1. 「エクスポート」をクリックします。

sbsar ファイルフォーマットをサポートする任意のソフトウェアで、マテリアルを表示されるパラメーターと一緒に使用できるようになりました。
