---
helpx_url: 'https://helpx.adobe.com/jp/substance-3d-sampler/filters.html'
breadcrumb-title: ''
description: Substance 3D Samplerのフィルターを使用して、プロシージャルな効果や画像ベースの効果を持つマテリアルを編集、強化、作成する方法を説明します。
helpx_creative_field: ''
helpx_description: Sampler > Filters
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: フィルター
user-guide-description: ''
user-guide-title: ''
source-git-commit: dc832dc546735437051226f4e1e731b55147b3ea
workflow-type: tm+mt
source-wordcount: '199'
ht-degree: 1%

---


# フィルター

>[!IMPORTANT]
>
> 環境光とメッシュのサポートは、Sampler V5.2のリリースで削除される予定です。 環境光の除去には、HDRI ツールとフィルターの除去も含まれます。

Adobe Substance 3D Samplerでは、主にフィルターを使用して、アセットを編集および調整します。 Samplerには、次の種類のフィルターがあります。

* [ジェネレーター](../filters/generators/generators.md) – 素材に新しい要素を追加します。
* [調整](../filters/adjustments/adjustments.md) – マテリアルのチャンネルの値を調整します。
* [ツール](../filters/tools/tools.md) – 技術的な問題を見つけて修正します。
* [HDRI ツール](../filters/hdri-tools/hdri-tools.md) – 環境光に固有のフィルター。
* [摩耗と仕上げ](../filters/wear-and-finish/wear-and-finish.md) – 素材の外観を変更します。

Adobe Substance 3D Designerを使用して独自のフィルターを作成することができます。[方法については、こちらをご覧ください](custom-filters.md)。

フィルターは、様々なテクノロジーに基づいて作成できます。

* Substance Designerで作成されたプロシージャルフィルター
* C++で直接作成された画像処理フィルターや人工知能を使用した画像処理フィルター

ほとんどのフィルターは、マテリアルまたは画像で使用できます。 一部のフィルターには、チャンネル設定に関する特定の要件があります。期待どおりにフィルターが機能しない場合は、ドキュメントでフィルターを確認して、使用方法ガイドを参照してください。
