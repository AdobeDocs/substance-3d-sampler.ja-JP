---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/features-and-workflows/texture-import.html"
breadcrumb-title: ''
description: Substance 3D Samplerにテクスチャを読み込んで、マテリアルの作成ワークフローで既存の画像ファイルを使用する方法について説明します。
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > Texture Import
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: テクスチャの読み込み
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 8%

---


# テクスチャの読み込み

![](../assets/Capture-decran-2025-02-19-162128.png.img.png)

**テクスチャの読み込み**&#x200B;テンプレートは、複数の画像を読み込み、ファイル名に基づいて適切な出力チャンネルに自動的に接続します。

チャンネルマッチングは、以下に詳述する特定の命名規則に基づいています。 重複または一致しないテクスチャの場合、インターフェイスで画像がそのようにマークされます。

## OpenPBR

Samplerは、次のOpenPBR IDを持つファイルをマテリアル内の対応するチャンネルと一致させます。

>[!NOTE]
>
> Height・チャネルIDは、ASMで使用されるIDと同じです。


| OPENPBR ID | SBSARの使用状況 |
| --- | --- |
| base_weight | baseWeight |
| base_color | baseColor |
| base_metalness | 金属度/メタリック |
| base_diffuse_roughness | baseDiffuseRoughness |
| Specularの太さ | specularWeight |
| Specularカラー | specularColor |
| Specular_ラフネス | 鏡面反射光の粗さ/粗さ |
| Specular_ラフネス_異方性 | specularRoughnessAnisotropy/anisotropyLevel |
| Specular_ior | specularIOR/IOR |
| transmission_weight | transmissionWeight |
| transmission_color | transmissionColor/absorptionColor |
| transmission_深度 | transmissionDepth/absorptionDistance |
| transmission_散乱 | transmissionScatter |
| transmission_散乱_異方性 | transmissionScatterAnisotropy |
| transmission_dispersion_scale | transmissionDispersionScale |
| transmission_dispersion_abbe_number | transmissionDispersionAbbeNumber |
| subsurface_weight | subsurfaceWeight/半透明度 |
| subsurface_color | subsurfaceColor/scatteringColor |
| subsurface_radius | subsurfaceRadius/scatteringDistance |
| subsurface_radius_scale | subsurfaceRadiusScale/scatteringDistanceScale |
| subsurface_散乱_異方性 | subsurfaceScatterAnisotropy |
| coat_weight | coatWeight/coatOpacity |
| coat_color | coatColor |
| coat_roughness | coatRoughness |
| coat_roughness_異方性 | coatRoughnessAnisotropy |
| coat_ior | coatIOR |
| coat_darking | coatDarking |
| fuzz_weight | fuzzWeight/sheenOpacity |
| fuzz_color | fuzzColor/sheenColor |
| fuzz_roughness | fuzzRoughness/sheenRoughness |
| emission_weight | emissionWeight |
| emission_luminance | emissionLuminance |
| emission_color | emisiveColor/emisive |
| thin_film_weight | thinFilmWeight |
| 薄膜Thickness | thinFilmThickness |
| thin_film_ior | thinFilmIOR |
| 不透明 | 不透明 |
| 薄い_壁 | 薄い壁 |
| 法線 | 法線 |
| 正接 | 正接 |
| coat_normal | coatNormal |
| coat_tangent | coatTangent |

## Adobe Standard Material

各チャンネルでサポートされているファイル命名規則を以下に示します。

| **チャネル** | **Adobe Standardマテリアル** |
| --- | --- |
| **環境オクルージョン** | <ul><li>環境閉塞</li><li>ao</li><li>オクルージョン</li><li>ambient_occlusion</li></ul> |
| **基本色** | <ul><li>ベースカラー</li><li>カラー</li><li>アルベド</li><li>base_color</li><li>ベース</li><li>col</li><li>カラー</li><li>base_color</li><li>基底色</li></ul> |
| **拡散** | <ul><li>拡散</li><li>diff</li></ul> |
| **放射体** | <ul><li>発光</li></ul> |
| **光沢** | <ul><li>光沢</li><li>グロス</li></ul> |
| **Height** | <ul><li>高さ</li><li>heightmap</li><li>ディスプレイスメント</li><li>disp</li></ul> |
| **メタリック** | <ul><li>メタリック</li><li>mtl</li><li>金属性</li></ul> |
| **標準** | <ul><li>法線</li><li>nrm</li></ul> |
| **不透明度** | <ul><li>不透明</li><li>アルファ</li></ul> |
| **粗さ** | <ul><li>ラフネス</li><li>粗面</li></ul> |
| **Specular** | <ul><li>反射</li><li>仕様</li></ul> |
| **Specular level** | <ul><li>specularlevel</li><li>Specularレベル</li></ul> |

