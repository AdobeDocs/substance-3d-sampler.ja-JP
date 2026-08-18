---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-4-4substance-3d-sampler.html"
breadcrumb-title: ''
description: テキストからテクスチャの変換機能や画像からテクスチャの変換機能などの生成ワークフローについて詳しくは、 Substance 3D Sampler version 4.4のリリースノートを参照してください。
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: バージョン4.4
user-guide-description: ''
user-guide-title: ''
source-git-commit: 6cc0519fb8c0f74fa805691ec4adb9e449a627d5
workflow-type: tm+mt
source-wordcount: '407'
ht-degree: 0%

---


# バージョン4.4

<b>Substance 3D Sampler 4.4</b>では、テキストからテクスチャ、テキストからパターン、および画像からテクスチャという3つの新しい生成ワークフローがベータ版として導入されています。

<b>AI生成機能は、Adobeアカウントが必要なため、Adobe版</b>でのみ利用できます。 そのため、これらの機能はSteamでは<b>利用できません</b>。

*リリース日： 2024年5月23日*

## Text-to-texture

![](../assets/textToTexture_whatNewPanel.png)

テキストからテクスチャへの変換を使用すると、<b>テキストプロンプト</b>を使用してマテリアルを作成する新しい方法を試すことができます。 詳細なテキストの説明からタイル状のテクスチャを作成し、画像間フィルターまたは任意のSamplerフィルターを使用して結果を基に独自の結果を作成できます。

## Image-to-texture

![Image-to-texture](../assets/imagetoText_whatNewPanel.png "Image-to-texture")

Image-to-textureを使用すると、非正方形および非タイリングの場合でも、<b>独自の参照画像</b>からタイリングされた正方形のテクスチャを作成できます。 これにより、完全なプロンプトを記述しなくても、目的の結果に近づけることができます。\
Image-to-textureを使用すると、既に作成したコンテンツからバリエーションを作成できるため、時間を節約できます。

## Text-to-pattern

![テキストからパターンへのイラスト画像](../assets/patterns_whatNewPanel.png)

テキストをパターン化する機能では、<b>テキストプロンプト</b>を使用して、四角形のタイリングパターンを生成します。 次に、布地織りフィルターでベースカラーとして使用して元の布地のマテリアルを作成し、パターンフィルターの入力などとして使用できます。

## リリースノート

*（リリース：2024年5月23日）*

<b>追加済み</b>:

* [Application] 3D キャプチャキャッシュが別のサブフォルダーに保存されるようになりました
* [Generative AI] Image to Texture (Beta)
* [Generative AI]テキストをパターン化（ベータ版）
* [Generative AI]テキストをテクスチャに（ベータ版）
* [スクリプト]アセットに「resource」プロパティが追加されました
* [スクリプト]レイヤーに「output\_usages」プロパティが追加されました

<b>修正済み：</b>

* [アプリケーション]破損したプロジェクトファイルを開くとクラッシュする
* [アプリケーション]プロジェクトに破損したアセットが含まれているとクラッシュする
* [アプリケーション] Windowsでモニターのプラグを抜くとクラッシュする
* [アプリケーション] Windowsタスクバーのアプリケーションアイコンが正しくない
* [アプリケーション]メイン構成ファイルが破損すると、ファイルが削除される場合がある
* [アプリケーション]パネルがポップアップの前に表示されます
* [コンテンツ]テクスチャジェネレータのサムネイルがぼやけている
* [書き出し] .sbs/.sbsarを書き出すと、読み込まれた画像から生成された不透明度チャンネルが壊れる
* [フィルター]入力レイヤーによっては、アップスケールがクラッシュすることがあります
* [Generative AI]サービスから予期しない結果を受け取ると、クラッシュする可能性がある
* [スクリプト]環境変数からプラグインを自動読み込みするとクラッシュする
* [スクリプティング] APIで出力の使用を割り当てるときにクラッシュする可能性がある
