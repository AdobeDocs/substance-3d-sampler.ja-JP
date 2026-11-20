---
description: 新機能、改善点、およびワークフローの機能強化について詳しくは、 Substance 3D Samplerバージョン6.1のリリースノートを確認してください。
title: バージョン6.1
hold: true
source-git-commit: 99bb504f8dd5c485bf0d208a85cc3825d186c55f
workflow-type: tm+mt
source-wordcount: '1167'
ht-degree: 0%
---

# バージョン6.1

**Kouign amann** （ブレトンのレイヤーペストリー）

![代替テキスト](../../help/assets/Sampler_splash_large.jpg)

このリリースでは、パフォーマンスモードが導入され、誰でもワークフローを遅くすることができる設定をオフにできます。また、安定性が自動的に向上して、軽量のハードウェア上のユーザーを保護します。

主な新機能は次のとおりです。

## パフォーマンスモード

Samplerでは、より高速で応答性の高いエクスペリエンスを実現します。 新しい&#x200B;**パフォーマンスモード**&#x200B;では、ワークフローを遅くするすべての設定（解像度の制限、シャドウ、ディスプレイスメントの画質、パストレース）をまとめることができます。 パフォーマンスと応答性を向上させる必要のない機能をオフにします。

詳細情報&#x200B;[*こちら*](https://www.adobe.com/go/substance-3d-sampler-6.1-performance-mode_jp)

![](../assets/v6.1/6_1-Performance_Mode.png)

## 最小仕様のマシンのサポートを改善

お使いのハードウェアが[最小仕様](../getting-started/system-requirements.md)を下回ると、Samplerが自動的に調整されて状態が安定します。 動作が遅くなったり、クラッシュが発生したりする可能性が最も高い機能は、自動的にオフになります。

詳細情報&#x200B;[*こちら*](https://www.adobe.com/go/substance-3d-sampler-6.1-low-specs-mode_jp)

![](../assets/v6.1/6_1-Checked.png)

## V6.1リリースノート

*（リリース：2026年11月19日）*

## 追加日

* &lbrack;Application&amp;rbrack；最小ハードウェア要件の警告をレポートする新しい方法
* &lbrack;Captis&rbrack;オプションを追加して、4と8の偏光角度から選択
* &lbrack;Captis&rbrack; New Captisクイックアクション
* &lbrack;Export&amp;rbrack；書き出しエラーをユーザーに適切にレポートする
* &lbrack;Export&rbrack; Unreal エンジン 4の書き出しプリセットを更新（Unreal エンジン 5に名前変更）
* &amp;lbrack；パフォーマンス&rbrack;ファイルからのアセット作成が非同期になりました
* &lbrack;Performance&rbrack;メインスレッドからワーカースレッドにワークロードを移動します
* &amp;lbrack；パフォーマンス&amp;rbrack；新しいパフォーマンスモード
* &lbrack;Project&rbrack;プロジェクトの保存に失敗した場合にユーザーに警告
* &lbrack;Scripting&rbrack;アセットの新しいgenerate_thumbnailメソッドとリソースの新しいtypeプロパティ
* &amp;lbrack；スクリプト&rbrack; Pythonモジュールから3Dビュースナップショットをファイルにレンダリング
* &lbrack;UI&rbrack;ドロップゾーンの任意の場所をクリックすると、ファイルダイアログが開きます
* &lbrack;UI&rbrack;ツール（イコライズ、切り抜き、タイリング、変形、修復、カラーなど）への左側のナビゲーションバーショートカット
* &lbrack;UI&rbrack; qt-spectrumをアップグレードして最新のアイコンを取得

## 固定

* &lbrack;3D ビュー&amp;rbrack；直ちにUV オフセットと回転を修正、OpenPBRの標準スケールを除去
* &lbrack;3D ビュー&rbrack; ビューポートの削除中にステージの編集が行われないようにして、クラッシュを防止します。
* &lbrack;3D ビュー&amp;rbrack；表示されているアセットを変更するときに、ディスプレイスメント(Height)情報を適切に削除する
* &lbrack;3D ビュー&rbrack; メッシュの削除時にドキュメントを正しく更新する
* &lbrack;Application&rbrack;ダイナミックフィルタデバッグ情報の計算時にサーフェスがアクティブなままであることを確認する(&amp;R)
* &lbrack;Application&rbrack; シーンの終了時にクラッシュを修正
* &lbrack;Application&rbrack; Asset Databaseサービスのシャットダウン中にアセットを削除する際に発生する可能性のあるクラッシュを修正
* &lbrack;Application&rbrack; クラッシュを防ぐためにキャッシュデバッグ情報スレッドを安全にする
* &lbrack;Application&rbrack; nodeがアクセス前にnullでないことをテストしてクラッシュを防ぐ
* &lbrack;Application&amp;rbrack；空のベクトルの最初の要素へのアクセスが原因で発生するクラッシュを防ぐ
* &lbrack;Application&rbrack; invalidateVisibleIfsのクラッシュを防止する
* &lbrack;Application&rbrack;データベースサービスの停止中にアセットを作成する際にクラッシュを防止する
* &amp;lbrack；アプリケーション&amp;rbrack；終了時に競合状態を回避
* &amp;lbrack；アセット&rbrack;リソースが適切にロックされた状態で保護されていることを確認
* &lbrack;Captis&rbrack; Bug with intensity value in manual mode
* &lbrack;Captis&rbrack;バックエンドで許可されているサイズより大きいゾーンをユーザーが選択できないようにする
* &amp;lbrack；チャンネル設定&rbrack; ASMでSpecularColorが二重に発生する
* &amp;lbrack；チャンネル設定&amp;rbrack；文字列から作成された使用法のIDを修正
* &lbrack;Content&rbrack; Atlas Scatterの不透明度の問題
* &lbrack;Content&rbrack; Embroideryフィルターにメタリック機能がありません
* &lbrack;Content&rbrack; Fix Perioentation filter
* &lbrack;Content&rbrack; Fix category of Stylization filter and some fix in resources panel
* &lbrack;Content&rbrack; Update Fill filter
* &lbrack;Creative Cloud&rbrack; Creative Cloud内の3Dアセットへのパスを修正
* &lbrack;エンジン&rbrack;ジョブが取り消されているときにエンジンデータにアクセスするとクラッシュが発生しない
* &lbrack;Export&amp;rbrack；構造体のツリーがnullでないことを確認するために防御コードを追加します。
* &lbrack;SBS生成のクラッシュを回避するための書き出し&amp;rbrack；防御コード
* &lbrack;Export&rbrack;カスタム使用状況がエンジンで認識されている場合でも、出力を有効にする
* &amp;lbrack；書き出し&amp;rbrack；書き出しプリセットを修正
* &lbrack;Export&rbrack; 法線マップがUSDでRAWとして書き出される
* &lbrack;Export&rbrack;プリセットを使用して書き出す場合に、使用法の代わりに出力ラベルを使用する
* &lbrack;表示されるパラメーター&rbrack;ダイナミックフィルターの表示されるパラメーターを修正
* &lbrack;表示されるパラメーター&amp;rbrack；名前の変更時に表示されるパラメーターの更新を修正
* &lbrack;Filters&amp;rbrack；各プラットフォームのすべての実行で、動的フィルターのツィーク識別子が同一であることを確認
* &amp;lbrack；フィルター&rbrack;サポートされていない使用状況を自動タイリングマップ選択で非表示
* &amp;lbrack；画層&amp;rbrack；画層の表示設定を変更すると、常に構造が再作成されます。
* &lbrack;クローンスタンプを何かの上に統合すると、レイヤーがクラッシュする&rbrack;
* &amp;lbrack；レイヤ&rbrack; スタックにジェネレータを直接挿入すると、ツイークとノード名が正しく設定されるようになりました
* &lbrack;Layers&rbrack; Inserting a generator with Fill correct a pickerにテクスチャが表示されます
* &lbrack;Localization&amp;rbrack；中国語の文字セットのコンプライアンスをGBに修正18030
* &lbrack;クローンスタンプにペイントした後に保存時のプロジェクト&rbrack;クラッシュ
* &lbrack;Project&rbrack;セッション名とプロジェクト名が実際に保存されていることを確認
* &amp;lbrack；プロジェクト&rbrack;ツリー保存時のクラッシュを防ぐ
* &lbrack;Project&amp;rbrack；破損したプロジェクトをデータベースから復元すると元に戻る
* &amp;lbrack；クイックアクション&rbrack; スタックに画像がない場合に画像選択ポップアップを表示
* &amp;lbrack；クイックアクション&amp;rbrack；クイックアクションの問題を修正；クイックアクションをキャンセルしてもクイックスタートが閉じられない
* &amp;lbrack；クイックアクション&amp;rbrack；読み込みテクスチャで、一部のチャンネルを有効にするかどうかを確認する
* &amp;lbrack；クイックアクション&rbrack;クイックアクションの読み込みに失敗した場合のクラッシュを防ぐ
* &amp;lbrack；クイックアクション&rbrack;クイックアクションコンテンツを更新
* &amp;lbrack；レンダリング&rbrack; ASM マテリアルのcombineNormalAndHeightを修正
* &amp;lbrack；レンダリング&rbrack; Vulkanで表示可能なテクスチャの使用状況を修正
* &amp;lbrack；レンダリング&amp;rbrack；一意の使用状況の出力が変更されたときにツリーをダーティにマークする
* &amp;lbrack；レンダリング&amp;rbrack；計算するツリーノードの計算に正しい参照構造を使用
* &lbrack;Scripting&amp;rbrack；書き出し中に問題が発生した場合にストールしない
* &lbrack;Scripting&rbrack; import_images()が読み込まれたレイヤーを返すことを確認
* &amp;lbrack；スクリプト&amp;rbrack；画像アセット参照への画像の微調整の設定が失敗する
* &lbrack;Scripting&rbrack; get_filters()が動的フィルターを返しません
* &lbrack;Thumbnail&rbrack;サムネール生成時のクラッシュを修正
* &lbrack;Thumbnail&rbrack;レイアウト変更時にサムネールジェネレータを再作成
* &lbrack;UI&rbrack;アセットを変更すると、Heightスケールがスライダーの最大値に設定されることがある
* &lbrack;UI&rbrack;テクスチャの描画は、テクスチャピッカーをリアルタイムで更新します。
* &lbrack;UI&amp;rbrack；最大化されていない状態でフルスクリーンモードに入ると、ウィンドウ全体が塗りつぶされるようになりました。
* &lbrack;UI&rbrack; Substanceマガジンへの壊れたリンクを修正
* &lbrack;UI&amp;rbrack；書き出しのポップアップマージンを修正
* &lbrack;UI&rbrack;セクションのタイトルサイズを修正
* &lbrack;UI&amp;rbrack；文字列内の誤りを修正する
* &lbrack;UI&rbrack; LinuxファイルダイアログでGTKプラグインを使用
* &lbrack;UI&amp;rbrack；絵文字を表示する際のクラッシュを防ぐ
* &lbrack;UI&rbrack; .ssaファイルを「Adobe Substance 3D Samplerアーカイブ」として名前変更（バージョンまたはベータ版を除く）
* &lbrack;UI&rbrack;マウス使用時にフリッカー可能な減速を復元
* &lbrack;UI&rbrack; 「新規マテリアルの作成」ダイアログの小さな修正
