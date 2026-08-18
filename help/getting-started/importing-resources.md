---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/getting-started/importing-resources.html"
breadcrumb-title: ''
description: Substance 3D Samplerに画像やSubstanceファイルなどのリソースを読み込んで、マテリアルの作成ワークフローを強化する方法について説明します。
helpx_creative_field: ""
helpx_description: Sampler > Getting Started > Importing Resources
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: リソースのインポート
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '279'
ht-degree: 1%

---


# リソースを読み込み

Samplerでは、画像やSubstanceファイルなどの外部リソースを使用してプロジェクトを編集できます。 ファイルをプロジェクトに読み込むには、次のいずれかのオプションを使用します。

* ファイルエクスプローラーからSamplerウィンドウにファイルをドラッグ&amp;ドロップします。 読み込みウィンドウが開き、読み込みの処理方法を変更するオプションが表示されます。

![](../assets/importing-resources-Importwindow.png)

* <b>左側のバー</b>で、<b>コンテンツの取得</b>ボタンを使用して、<b>レイヤースタックに読み込み</b>または<b>アセットに読み込み</b>のいずれかを選択します。 どちらのオプションでもファイルエクスプローラーが開き、読み込むファイルに移動して選択できます。
  * <b>レイヤースタックに読み込み</b>では、現在のプロジェクトのファイルを読み込みます。
  * <b>アセットに読み込む</b>は、ファイルを読み込んで、任意のプロジェクトからアクセスできるようにします。

![](../assets/Project_CreateNew.png)

* <b>レイヤー</b>パネルで、レイヤーが作成されていない場合は、使用可能なリンクを使用してファイルを読み込み、素材のベースを形成できます。

>[!NOTE]
>
> リソースはリンクされており、読み込まれていません。 その結果、リソースファイルが移動または削除されると、そのリソースで作成されたマテリアルまたはコンテンツに影響します。 そのため、Samplerアセット専用のフォルダーを使用することをお勧めします。
> 
> デフォルトでは、Samplerに含まれているアセットは、 C:\Program Files\Adobe\Adobe Substance 3D Sampler\Resources\assetsに保存されます

## サポートされているファイル形式

| タイプ | 説明 |
| --- | --- |
| <b>ビットマップ/画像</b> （JPEG、PNGなど） | <b>レイヤー</b>パネル、またはイメージ入力を許可するSBSARまたはフィルターパラメーターに、ビットマップをドラッグ&amp;ドロップしたり、読み込んだりすることができます。 |
| <b>Substanceパッケージ</b> (SBSAR) | SBSARファイルは、<b>アセット</b>パネルまたは<b>レイヤー</b>パネルに読み込むことができます。 |
