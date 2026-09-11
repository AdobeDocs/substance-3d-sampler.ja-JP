---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/pipeline-and-integrations/hp-z-captis-support/faq-hp-z-captis-support-in-sampler.html"
breadcrumb-title: ''
description: Substance 3D SamplerでのHP Z Captisのサポートに関するよくある質問にアクセスして、ハードウェアの統合と使用方法に関する回答を検索します。
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: SamplerでのHP Z CaptisサポートのFAQ
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '1547'
ht-degree: 0%

---


# よくある質問

## マテリアルサンプル

+++Captisはどのようなユースケースをカバーしていますか？
このソリューションは、業界を超えたユースケース（自動車、アパレル、製品デザイン、メディア&amp;エンターテインメント、アーキテクチャなど）を対象としています。 スタジオモードではデスクトップでのキャプチャが可能です（再現性、効率性、シンプル）。一方、エクスプローラーモードではモバイルでのキャプチャが可能です（外出先でも柔軟に行え、あらゆる状況に対応できます）。

+++

+++Captisでスキャンおよびキャプチャできるマテリアルの種類を教えてください。
複数のクリアコートレイヤーを使用する場合を除き、あらゆる種類のマテリアルをスキャンしてキャプチャできます（カーペイントは、Captisスコープから除外されます）。 特定のマテリアルによっては、結果を最適化するためにSamplerで追加の処理が必要になる場合があります。 処理アルゴリズムは、時間の経過とともに継続的に最適化されることに注意してください。

+++

+++マテリアルのサンプルのサイズや形状にどのような制限がありますか？サンプルは平らである必要がありますか？
カプティスは、様々なマテリアルサンプルのサイズや形状をスキャンすることができます。 サンプルをサンプル皿に盛り付けるためにマグネットで送られます。 Captisを使用してマテリアルサンプルをキャプチャするには、いくつかのモードがあります。

* スタジオモード：机の上にスタジオベースを置いて、スタジオ内で、または工場で、Captisは最大30cm x 30cmのサンプルを取ります – 不透明度のためにバックライト付き。 サンプルトレイの深度は1.8 CMです。

* エクスプローラーモード：エクスプローラーリングは撮影現場、撮影現場、またはユニークな場所で使用でき、30cm x 30cmより大きいサンプルでも柔軟にキャプチャできます。 現在の制限：エクスプローラーモードはまだ初期バージョンであり、最適化されていません（2024年7月29日時点リリース）。

+++

## ソフトウェア

+++HP Z Captisデバイスを使用するには、ソフトウェアのサブスクリプションまたはライセンスが必要ですか？
Captisデバイスを使用するには、Substance 3Dサブスクリプションと同じ条件と利用条件に基づいてSubstance 3Dコレクションで利用可能なSubstance 3D Sampler Enterprise、Teams、またはUniversityライセンスが必要です。

デバイス(HP Z Captis)とライセンス(Substance 3D Sampler)は別売りです。

+++

+++AdobeのSubstanceスイートにはどのレベルの統合が存在しますか？
HP Z Captisは、Adobe Substance 3D Samplerで完全に制御および操作できます。キャプチャをSubstance 3D Samplerでプレビューして起動すると、PBRチャンネルがレイヤーとして自動的に読み込まれ、3Dマテリアルが作成されます。 Samplerで利用できるすべてのツールとフィルターを使用して、マテリアルを引き続き処理できます。

キャプチャしたマテリアルがSubstance 3D Samplerに保存されると、Substance 3D suite(Substance 3D Designer、Painter、Stager)の任意のアプリケーションと、Substanceをサポートする任意のサードパーティのアプリケーション（3DS Max、Maya、Blender、Unreal Application、CLO、Browzwear、VRED、Rhino、Cinema4Dなど）に書き出すことができます（完全な一覧はこちらを参照してください： <https://www.adobe.com/jp/products/substance3d/plugins.html>）。

+++

+++CaptisでSubstance 3D Samplerを使用する際に推奨される仕様を教えてください。
Samplerのハードウェア仕様は、[こちら](system-requirements-to-use-hp-z-captis.md)から入手できます。

+++

+++HP Z Captisワークフローは、WindowsとMacの両方で利用できますか？
2025年2月20日のリリース以降、HP Z Captisを使用したSamplerワークフローは、Windowsでのみ使用できます。

+++

+++HP Z Captisを使用したSubstance 3D Samplerのワークフローはどこにありますか？
2025年2月20日のリリース以降、Creative CloudデスクトップアプリからダウンロードしたSubstance 3D Samplerの通常のビルドの一部として、CaptisのワークフローでAdobe Substance 3D Samplerにアクセスできます。 Adobeのプレリリース版からダウンロードする必要はありません。

+++

+++まだ利用できない機能
*2025年8月現在の制限（Sampler 5.1.0ビルド）:*

* HP Z Captisワークフローを使用したSamplerは、現時点ではWindowsでのみ使用できます。

* 現在書き出されている5つのマップは、Base color、ラフネス、法線、Height、不透明度です。

* エクスプローラーモードはまだ初期バージョンで、まだ最適化されていません。

* 現在のタイリングフィルターを使用して、Sampler レイヤースタックでタイリングが行われます。

+++

+++どのようなPBRチャネルが利用できますか？
2025年8月7日のリリース時点で、書き出されている5つのマップは、Base color、ラフネス、通常、Height、不透明度です。 現在の処理パイプラインは、まだメタネスマップを処理していません。

+++

+++タイリングは自動的に行われますか？
タイリングは、現在のタイリングフィルターを使用してSampler レイヤースタックで行われます。

自動タイリングフィルターを使用すると、定義された繰り返し構造または小さなパターンを持つマテリアルを、各方向に3つ以上のパターンで自動的に並べることができます。 このフィルターについて詳しくは、ドキュメントの[専用セクション](../../filters/tools/auto-tiling.md)を参照してください。

+++

+++スキャンしたマテリアルは、どの形式で書き出せますか？
HP Z Captisは、Adobe Substance 3D Samplerがネイティブに運用しています。 HP Z Captisは、64枚のRAW画像（ローカルフォルダーから取得可能）とPBRマップ（RAW画像から処理され、Substance 3D Samplerに自動的に読み込まれる）をキャプチャします。 Substance 3D Samplerは、キャプチャ後にSampler レイヤースタックに自動的に読み込まれるPBRチャンネルに基づいて3d マテリアルを作成します。

Adobe Substance 3D Samplerから、Substance 3D Samplerで使用可能な任意の書き出し形式(Substanceファイル（.SBSおよび.SBSARファイル）で、または.PNG、.JPG、.TIFFを含むビットマップテクスチャ)でデジタルマテリアルを書き出すことができます（Samplerのドキュメントのwebページ[https://helpx.adobe.com/jp/substance-3d-sampler/getting-started/export.html](../../getting-started/export/export.md)を参照）。

+++

+++キャプチャ中のLDRとHDRの違いは何ですか？
プレビュー中に、LDR（ローダイナミックレンジ）とHDR(ハイダイナミックレンジ)から出力の種類を選択できます。\
LDRが選択されている場合でも、HDRマップはキャプチャされてデバイスに保存されます。\
LDRを選択すると、Samplerやsbsar ファイルを使用するサードパーティアプリでプロジェクトのサイズを管理しやすくなります。

+++

## 処理中

+++特定のファイル形式、規格や仕様、またはサードパーティのアプリケーションを使用している場合、現在の3DパイプラインでCaptisを使用する方法を教えてください。
HP Z Captisは、Adobe Substance 3D Samplerがネイティブに運用しています。 Substance 3D Samplerでマテリアルサンプルをキャプチャしてデジタル化したら、デジタルマテリアルをシームレスに書き出すことができます。

Substance 3Dエコシステムの任意のアプリケーション（様々な書き出し形式をサポートするSubstance 3D DesignerまたはSubstance 3D Painterなど： https://experienceleague.adobe.com/ja/docs/substance-3d/general-knowledge/ecosystem/import-and-export-formats）。

3DS Max、Maya、Blender、C4D、Rhino、Browzwear、CLOなどのSubstanceファイルフォーマットを統合するアプリケーションでは、すべて次のリストを参照してください： <https://www.adobe.com/jp/products/substance3d/plugins.html>。 ここに記載されていないアプリケーションを使用している場合は、いつでもPBR テクスチャイメージを書き出し、そのSubstanceファイル形式をネイティブにサポートしていないアプリケーションに手動で接続できます。

+++

+++地図を作るために何枚の写真が撮られていますか。
[8枚のライトパネル+ 1枚のバックライト] x [8枚の偏光状態] x [HDRのブラケティング露出8] x [ノイズを軽減するための4枚の上書き] = 2048 + 256 （バックライト）

+++

## デバイス管理

[HPのWebサイト](https://www.hp.com/us-en/workstations/z-captis.html "HP Z Captis")で、デバイスとその仕様の詳細をご確認ください。

+++デバイスのIPアドレスを変更できますか？
デバイスのIPアドレスを変更するには、WindowsファイルC:\Windows\System32\drivers\etc\hosts.txt byに次の余分な行を追加します。

例えば、192.168.55.1 captis-deviceを追加し、<b>Samplerの設定/ストレージとキャッシュ/マテリアルキャプチャ/Captisアドレス</b>でIPをcaptis-deviceに置き換えることができます

+++

## 使用に関する問題

+++SamplerでHP Z Captisが認識されない。
HP Z CaptisがUSB 3.0ポートに接続されていることを確認します。

USBケーブルがコーンではなくHP Z Captisのベースに接続されていることを確認します。

+++

+++Samplerのウィンドウでプレビューが完全に黒くなる。
カメラ防止機能が取り外されていることを確認します。

+++

+++HP Z Captisからマイコンピューターへのファイルのコピーに時間がかかる。
HP Z CaptisがUSB 3.0ポートに接続されていることを確認します。

マテリアル画像とフォトメトリック画像の両方を取得するように要求された場合、コピーに時間がかかるのは正常です。

+++

+++Samplerが画像をマイコンピューターにコピーしませんでした。 スキャンを再開する必要がありますか？
いいえ、ありません。 OSのファイルエクスプローラーを使用して、デバイスのコンテンツを参照し、Adobeフォルダーにあるイメージをコピーできます。

+++

+++メニューは、デバイスがリカバリモードであることを示します。
電源ボタンを数秒間押して、電源を切ります。 もう一度オンにします。

+++

+++コーンをベースからエクスプローラーリングに移動させましたが、もうスキャンできません。
HP Z Captisは、ベースまたはエクスプローラーリングから取り外す前にオフにすることをお勧めします。

+++

+++SBSARでのマテリアルの書き出しに時間がかかる。
プロパティパネルで、画像が32 bit浮動小数点形式でないことを確認します。

圧縮レベルを「なし」に設定して、書き出しを高速化することもできます。

+++

+++撮影したマテリアルと測光画像の保存先を変更します。
編集/環境設定/ストレージとキャッシュ/マテリアルキャプチャで、キャプチャしたマテリアルとPhotometryイメージを保存する場所を変更できるようになりました。

+++

+++ウィンドウが画面より大きく、サイズを変更できません。
Captisウィンドウはサイズ変更できません。 処理されない画面の拡大率を使用している可能性があります。 Captisは以下をサポートしています。

* 解像度：1920 x 1080
  * 最大倍率： 100%

* 最大倍率： 100%

* 解像度： 2560 x 1440
  * 最大倍率： 125%

* 最大倍率： 125%

* 解像度：3840 x 2160
  * 最大倍率： 200%

* 最大倍率： 200%

* 1920 x 1080未満の解像度はサポートされていません。



+++
