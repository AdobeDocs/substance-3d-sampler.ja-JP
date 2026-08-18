---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/features-and-workflows/adobe-standard-material.html"
breadcrumb-title: ''
description: Substance 3D SamplerでAdobe Standardマテリアルを使用して、Adobeのマテリアル標準と互換性のあるマテリアルを作成する方法について説明します。
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > Adobe Standard Material
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Adobe Standard Material
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '523'
ht-degree: 1%

---


# Adobe Standard Material

>[!NOTE]
>
> Substance 3D Samplerは、Adobe Standardマテリアルではなく、デフォルトで[OpenPBR](openpbr.md)マテリアルモデルになりました。


## 標準マテリアルプロパティ

## 基準サーフェスプロパティ

**基本色**

サーフェスのカラー。

**粗さ**

表面の滑らかさまたはマットの度合い。

![](../assets/surface-roughness.jpg)

**メタリック**

表面の金属光沢の度合い。

![](../assets/surface-metallic.jpg)

**不透明度**

サーフェスの可視性。

![](../assets/surface-opacity.jpg)

**環境オクルージョン**

空洞や折り目からの影により、光がサーフェスに当たらないようにします。

**Specular level**

サーフェス上の光の反射の強度。

![](../assets/surface-specularlevel.jpg)

**Specular edge color**

光の反射の色。 メタリックマテリアルの傾斜角度に影響します。

![](../assets/surface-specularedgecolor.jpg)

**標準**

バンプや亀裂などのサーフェスのディテールをシミュレートします。

**標準スケール**

通常の効果の強さ。

**標準とHeightを組み合わせる**

Heightテクスチャの上に法線テクスチャを適用します。

**Height**

バンプまたはジオメトリディスプレイスメントを使用してサーフェスのディテールを作成します。

**Heightスケール**

Heightのスケールをシーン単位で指定します。 バンプとディスプレイスメントの両方に適用されます。

**Heightレベル**

ディスプレイスメントゼロを表すHeightテクスチャの値。

**異方性レベル**

サーフェスに沿って1方向に伸びる反射の量。

![](../assets/surface-anisotropy.jpg)

**異方性角度**

異方性効果の反時計回りの回転。

**発光強度**

サーフェスから放出されるライトの強度。

![](../assets/surface-emission.jpg)

**発光色**

発光する光の色。

![](../assets/surface-emissioncolor.jpg)

**光沢の不透明度**

サーフェス上の微細な繊維やぼやけの効果をシミュレートします。

![](../assets/surface-sheen.jpg)

**光沢カラー**

光沢エフェクトのカラー。

![](../assets/surface-sheencolor.jpg)

**光沢の粗さ**

光沢エフェクトの柔らかさ。

![](../assets/surface-sheenroughness.jpg)

## 内部プロパティ

**半透明度**

サーフェスを透過できるライトの量。

![](../assets/interior-translucency.jpg)

**吸収カラー**

カラー光は吸収されるにつれて収束します。

**吸収の距離**

吸収カラーに達する前に光が通過するおおよその距離をシーン単位で表したもの。 0に設定した場合、Thicknessは吸収カラーに影響しません。

![](../assets/interior-absorptiondistance.jpg)

**屈折指数**

オブジェクトを通過するときに曲がる光の量。

![](../assets/interior-indexofrefraction.jpg)

**分散**

屈折したときにカラースペクトルが広がる量。

**サブサーフェスのスキャタリング**

散乱はサーフェスの下にライトを通過しますが、まっすぐに通過しません。

**散布カラー**

散乱光がサーフェスの下のカラーになります。

![](../assets/interior-scattercolor.jpg)

**散乱距離**

完全な散乱に達する前に、おおよその距離の光が進行しなければならない。

![](../assets/interior-scatterdistance.jpg)

**散乱距離スケール**

散乱距離の乗数。 カラーチャンネルによって異なる場合があります。

![](../assets/interior-scatterdistancescale.jpg)

**赤のシフト**

他の光の色よりも赤い光が先に進むように設定します。 肌に便利です。

![](../assets/interior-scatterredshift.jpg)

**レイリー散乱**

サーフェスの下をオレンジ色のライトが移動し、下を青色のライトが移動するように設定します。

![](../assets/interior-scatterraleigh.jpg)

**ボリュームThickness**

オブジェクトの境界ボックスに対するサーフェスの相対Thickness。 実際のThicknessが不明な場合に、内部効果に使用されます。

**ボリュームThicknessスケール**

ボリュームThicknessの乗数。

## コートのプロパティ

**コートの不透明度**

マテリアルの上にレイヤーをシミュレートします。 クリアコート、ラッカー、ワニスの作成に使用します。

![](../assets/coat-coatopacity.jpg)

**コートの色**

コートの色。

![](../assets/coat-coatcolor.jpg)

**コートの粗さ**

毛の表面がどれほど滑らかで艶消しされているのか。

![](../assets/coat-coatroughness.jpg)

**コートの屈折率**

光の量はコートを通る時に曲がる。

![](../assets/cooat-coatior.jpg)

**コートSpecular level**

斜めから見たときにコートに映る光の強さ。

![](../assets/coat-coatspecular.jpg)

**標準のコート**

毛の表面にバンプや亀裂などのサーフェスのディテールをシミュレートします。

![](../assets/coat-coatnormal.jpg)

**コート標準スケール**

コートの強さ通常の効果。
