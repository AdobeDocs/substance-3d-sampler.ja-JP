---
helpx_url: 'https://helpx.adobe.com/substance-3d-sampler/release-notes/all-changes.html'
breadcrumb-title: ''
description: Substance 3D Samplerのすべてのバージョンに加えられた変更とアップデートを確認し、機能の進化と改善点を経時的に追跡します。
helpx_description: Sampler > Release Notes > All Changes
title: すべての変更
user-guide-description: ''
user-guide-title: ''
source-git-commit: 275dc218870f111aa99533840a5aea4c3d22f0cf
workflow-type: tm+mt
source-wordcount: '24964'
ht-degree: 0%
---

# すべての変更

新機能からバグ修正まで、Substance 3D Samplerに加えられたすべての変更を再編成します。

## バージョン6

### **6.0.4**

*（リリース：2026年9月24日）*

**変更日**
[エンジン] Substance engineを9.6.1に更新する

**固定**
エンボスマスクに画像を追加するときに[レイヤー]クラッシュ
[セキュリティ]の一般的な修正

### **6.0.3**

*（リリース：2026年8月24日）*

**修正済み：**

[レンダリング]障害のあるNVIDIAドライバーの一時的な回避策を元に戻します

### **6.0.2**

*（リリース：2026年6月25日）*

**追加：**

* &lbrack;Assets&rbrack; Check sbsar version and warn users is the users is the too old to read it
* &lbrack;Captis&amp;rbrack；環境設定でCaptisフォトメトリックを保存するための戻るオプションを追加

**修正済み：**

* &lbrack;2D ビュー&rbrack;物理サイズが無効な場合、「物理比で表示」しません。
* &lbrack;Analytics&amp;rbrack；見つからない分析イベント
* &lbrack;Analytics&rbrack;クラッシュパッドがvk devicelostでクラッシュを報告するのを防ぐ
* &lbrack;Application&rbrack; nvidiaドライバのクラッシュを避けるため、終了時にvkdeviceを破棄しないでください
* &lbrack;Application&rbrack;リンクされたコレクションウォッチャー終了を修正+チャネルマネージャ
* &lbrack;Application&amp;rbrack；終了時にクラッシュを防止
* &lbrack;Content&rbrack; 「メタル仕上げ」フィルターはメタルに影響しません
* &lbrack;Content&rbrack;物理サイズが見つからない場合にダイナミックフィルターに追加
* &amp;lbrack；フィルター&amp;rbrack；非表示のアセットリストからコンテンツに応じた塗りつぶしを削除
* &amp;lbrack；レイヤー&rbrack; 「すべての設定をリセット」をクリックしても、「適用先」ドロップダウンがリセットされない
* &amp;lbrack；レイヤー&amp;rbrack；位置ウィジェットの最小および最大ツイークを修正
* &amp;lbrack；画層&rbrack;フィルタを正しく更新
* &lbrack;物理サイズ&amp;rbrack；あらゆる場所で物理スケールが機能することを確認し、ダイナミックフィルターを使用して物理サイズをokにする
* &amp;lbrack；プロジェクト&amp;rbrack；新しいアセットを作成する際に、アセットの解像度がデフォルト(2k x 2k)であることを確認する
* &amp;lbrack；プロジェクト&amp;rbrack；現在のプロジェクトを再度開く（以前のバージョンを開くのに使用）
* &lbrack;Project&rbrack; Samplerは、破損したプロジェクトのバックアップを復元することはできません。
* &amp;lbrack；レンダリング&rbrack;マテリアルサムネールを最大2Kの解像度でレンダリング
* &lbrack;UI&rbrack;ユーザがUIより高速な場合のクラッシュを防ぐための防御コード

### **6.0.1**

*（リリース：2026年5月21日）*

**追加：**

* &lbrack;Application&rbrack; 3Dオブジェクトまたは環境光を含むプロジェクトを開くときに警告を表示
* &lbrack;Captis&rbrack; UIを小さな画面に適応させる
* &lbrack;Captis&rbrack; Captis UIを更新
* &amp;lbrack；チャンネル設定&rbrack; ASMでSSSチャンネルを使用するときにSSSを自動的にアクティブ化
* &lbrack;エンジン&rbrack; Substance engineをバージョン9.4.3にアップデート
* &lbrack;Preset&rbrack; 「プリセットサムネール値を適用」をデフォルトでオンに切り替え
* &lbrack;Resources&rbrack;リソースパネルに「スターターアセット」ではなく「すべてのライブラリ」をデフォルトで表示
* &lbrack;Scripting&rbrack; Python関数を追加してレイヤーの「適用先」を管理
* &lbrack;UI&rbrack;アセットリストがレスポンシブになりました：アセットサイズがコンテナに適応します
* &lbrack;UI&rbrack;デフォルトで3D / 2D ビューを表示
* &lbrack;UI&rbrack; エクスプローラーからマテリアルをドロップする際にマテリアル最適化ポップアップを表示
* &lbrack;UI&rbrack;デバイスバーボタンのツールチップのフリップを有効にする

**修正済み：**

* &amp;lbrack；アプリケーション&rbrack;カラースペースの問題を修正
* &amp;lbrack；アプリケーション&amp;rbrack；設定アップデーターの修正(&amp;R)
* &lbrack;Application&rbrack;スキャンチャネルがautoに設定されている場合はアクティブにする(&amp;R)
* &lbrack;Application&rbrack;ホーム画面の「新規プロジェクト」ボタンで、以前の同じ名前のプロジェクトが消去されなくなりました
* &lbrack;Application&rbrack; macOSの終了時にクラッシュを防止
* &lbrack;Application&amp;rbrack；無効なアセット参照のアセットへのアクセスを防止
* &lbrack;Application&rbrack; TweakでVersionedImageからサーフェスにアクセスする際にクラッシュを防ぐ
* &lbrack;Application&amp;rbrack；存在しない場合にステージを削除するときにクラッシュを防ぐ
* &lbrack;Captis&rbrack; Samplerを閉じる前にCaptisが切断されていることを確認する
* &lbrack;Captis&rbrack; USB-2警告が2回表示されないようにする
* &amp;lbrack；チャンネル設定&rbrack; OpenPBRチャンネル名を修正
* &amp;lbrack；チャンネル設定&rbrack; OpenPBRチャンネルの長いラベルを更新する
* &lbrack;Content&rbrack; SSS値のメッシュ単位をメートルからセンチメートルに更新する
* &lbrack;Export&rbrack;デフォルト値がダイナミックフィルターに接続されていることを確認
* &lbrack;Export&amp;rbrack；画像がパフォーマンス向上のためにワーカースレッドに保存されるようになりました。
* &amp;lbrack；フィルター&rbrack;コンテンツに応じた塗りつぶしクラッシュでスケールをオンに切り替える
* &amp;lbrack；フィルター&rbrack;アセットパネルからダイナミックフィルターの場所を開けませんでした。
* &amp;lbrack；フィルター&amp;rbrack；自動タイリング調整ステップですべての設定をリセットを修正
* &amp;lbrack；フィルター&amp;rbrack；復元ツリー構造作成の使用不可処理
* &amp;lbrack；フィルタ&rbrack;アップスケールパラメータの正しいデフォルト値を設定
* &amp;lbrack；フィルタ&rbrack;ジェネレータが塗りつぶしレイヤー内にある場合でも更新する
* &amp;lbrack；レイヤー&amp;rbrack；入力レイヤーヘッダーまたはプレースホルダーレイヤーの名前変更を禁止
* &lbrack;Layers&rbrack;ポインタがダングリングしているためにレイヤ挿入時にクラッシュを防止する(&amp;R)
* &amp;lbrack；レイヤー&rbrack;レイヤー名の統合に含まれる画像の数が正しくありません
* &lbrack;Localization&amp;rbrack；言語の切り替え時にプリセット名が更新されるようにする
* &lbrack;Localization&rbrack;リソースパネルの複数の翻訳の問題
* &lbrack;Localization&rbrack; Quick Actions categories localization issues
* &lbrack;Performance&amp;rbrack；開いたセクションでのみツィークをロード
* &lbrack;Preferences&amp;rbrack；環境設定キャッシュパスが以前の値にリセットされるクリア
* &lbrack;Rendering&rbrack; Memory leak when using Path Tracer
* &amp;lbrack；レンダリング&rbrack;テクスチャがVulkanからアクセスされている間に削除されないようにする
* &amp;lbrack；レンダリング&rbrack;テクスチャ回転が0-1から0-360に変換されませんでした
* &lbrack;Scripting&rbrack; Pythonドキュメントから存在しないクラスを削除する
* &lbrack;Scripting&rbrack; selectedAssetは、選択されたアセットがない場合はNoneを返します
* &lbrack;Tools&rbrack; テクスチャ値をリセットするとペイントが停止し、パッチビューがクリアされる
* &lbrack;UI&amp;rbrack；何かが微調整された場合、プロパティパネルのセクションを閉じないでください
* &lbrack;UI&rbrack;表示した色の微調整ラベルがホバー時に非表示になる
* &lbrack;UI&rbrack;アセットリストのレスポンシブビヘイビアーを修正
* &lbrack;UI&rbrack; AssetItemツールチップのバインドループを修正
* &lbrack;UI&amp;rbrack；選択したプリセットグループのダブルクリックを修正
* &lbrack;UI&rbrack;イメージプレゼンターのドロップ領域を修正
* &lbrack;UI&amp;rbrack；すべての言語でボタンの付いたラベルを修正
* &lbrack;UI&rbrack;チャンネルリストポップアップで日本語のラインHeightを修正
* &lbrack;UI&rbrack; Fix onAccepted signal of lengthフィールド
* &lbrack;UI&amp;rbrack；左の長いコントロールアイテムでポップアップの幅を修正
* &lbrack;UI&rbrack;アセットアイテムのプレビューポップアップを修正
* &lbrack;UI&amp;rbrack；粗い/反射ピッカーを修正
* &lbrack;UI&amp;rbrack；文字列の省略記号を修正
* &lbrack;UI&amp;rbrack；文字列の切り詰めの問題を修正
* &lbrack;UI&rbrack;スイッチのツイークリセットボタンを修正
* &lbrack;UI&rbrack;カスタム書き出しプリセットが選択された場合にマテリアルモデルドロップダウンを非表示
* &lbrack;UI&amp;rbrack；書き出しのチャンネルリストから解像度を削除ポップアップ
* &lbrack;UI&rbrack;デフォルトのレイアウトにリセットすると、投影ビューアの設定が維持される(&amp;R)
* &lbrack;UI&rbrack; 「Photoshopで編集」および「Illustratorで編集」のメニュー項目を復元

**削除済み：**

* &lbrack;UI&amp;rbrack；画像読み込みレイヤーの「適用先」セクションを削除
* &lbrack;UI&amp;rbrack；初回起動時に自動的に開くクイックアクションツールチップを削除

## バージョン5

### **5.1.3イルフロッタンテ**

*（リリース：2026年1月6日）*

**追加：**

* &lbrack;Captis&rbrack;ファイアウォールがFTPプロトコルを無効にしている場合に警告を表示する

**修正済み：**

* &lbrack;Captis&rbrack;キャプチャ中に中断するとエラーが発生する可能性があります
* &lbrack;Captis&rbrack;キャプチャの最後に結果をダウンロードすると、多くのRAMが使用されます
* &lbrack;Captis&amp;rbrack；自動強度の直後にオートフォーカスを実行すると、エラーが発生する可能性がある
* &lbrack;Captis&rbrack; HDRの結果がサマリーパネルに表示されます
* &lbrack;UI&amp;rbrack；場合によっては、MacOSのフォルダーダイアログで正しいフォルダーが選択されないことがあります

### **5.1.2イルフロッタンテ**

*（リリース：2025年11月20日）*

**追加：**

* &lbrack;Application&rbrack;グラフィックデバイスの損失の検出、ユーザーへの警告、および正常な終了
* &amp;lbrack；レイヤー&rbrack;レイヤーを統合する際のメッセージングを改善
* &amp;lbrack；レイヤー&rbrack;イメージの読み込みと統合されたレイヤーのサムネールを改善
* &lbrack;Onboarding&rbrack;ホーム画面で学習コンテンツを更新
* &lbrack;Project&rbrack; クラッシュ前に最後に保存されたセッションの状態を復元する
* &lbrack;UI&rbrack;アプリケーションアイコンの更新

**修正済み：**

* &lbrack;Application&rbrack; レイヤースタックにマテリアルを挿入すると、macOSでクラッシュが発生する可能性があります
* &lbrack;Application&rbrack; macOSでの高負荷時にクラッシュが発生する可能性がある
* &lbrack;Application&rbrack;ビデオメモリがいっぱいのときにレイヤーを追加すると、クラッシュが発生する可能性があります
* &lbrack;Application&rbrack;プロジェクトを開くときに起こりうるクラッシュ
* &amp;lbrack；強度の自動調整後に自動フォーカスが間もなく実行された場合に失敗する&rbrack;
* &lbrack;Captis&amp;rbrack；最初のキャプチャ後の信頼性とパフォーマンスの問題
* &amp;lbrack；キャプチャの最後にファイルをコピーすると、速度が低下してエラーが発生する&rbrack;
* &lbrack;Captis&rbrack; Captisデバイス情報のクエリ時に小さなメモリリークが発生する
* &lbrack;Export&rbrack; Multi slider 表示されるパラメーターが破損した.sbsarファイルを生成
* &amp;lbrack；レイヤー&amp;rbrack；アセットの切り替え時に自動タイリングパターンがデフォルト値にリセットされる
* &lbrack;Layers&rbrack;デフォルトのカスタムbase colorが赤く表示される
* &amp;lbrack；レイヤー&rbrack; クローンスタンプの子レイヤーを部分的に統合すると、レンダリングに問題が発生する可能性があります。
* &amp;lbrack；レイヤー&rbrack;レンダリング中にレイヤースタックを微調整すると、クラッシュする可能性がある
* &lbrack;Layers&rbrack; ソースチャンネルの変更時に自動タイリング目標範囲ステップで予期しないエラーが発生する
* &amp;lbrack；プロジェクト&amp;rbrack；新規マテリアル作成時にサムネールが正しくない場合がある
* &amp;lbrack；クイックアクション&amp;rbrack；一部のクイックアクションの入力数が間違っています
* &lbrack;UI&rbrack;アクショングループボタンの幅が異なる
* &lbrack;UI&rbrack;テキストフィールドの「クリア」ボタンがフォーカスを失うことがある
* &lbrack;UI&rbrack;コンボボックスとテキストフィールドが大きすぎます
* &lbrack;UI&rbrack;アイコンとラベルが正しく位置合わせされていません
* &lbrack;UI&amp;rbrack；名前フィールドラベルが正しく配置されていません
* &lbrack;UI&rbrack;クイックアクションボタンのラベルが正しく配置されていない
* &lbrack;UI&rbrack;スライダが末尾の0を超えて表示されます。

**削除済み：**

* &lbrack;Generative AI&amp;rbrack；生成AI機能の削除。 *この機能はアプリケーションから削除され、3月5日に以前のバージョンのSamplerでサービスが停止されます。*

### **5.1.1イルフロッタンテ**

*（リリース：2025年9月18日）*

**追加：**

* &lbrack;2D ビュー&amp;rbrack；高解像度テクスチャ用に2D ビューをさらにズームアウト可能
* &lbrack;Captis&rbrack;ファイルをコピーする際の問題をユーザーに警告する(&amp;R)
* &lbrack;Layers&rbrack;レイヤーを複製する場合は、新しいレイヤー名に増分値を使用します

**修正済み：**

* &lbrack;2D ビュー&rbrack; クローンスタンプのすべてのプロパティをリセットした後にストロークをペイントすると、以前に作成したストロークが再び表示される
* &lbrack;Application&rbrack; &quot;Save current project?&quot; ポップアップで間違ったプロジェクト名が使用されています
* &lbrack;Application&rbrack; クラッシュ at exit
* &lbrack;Application&amp;rbrack；潜在的なクラッシュ
* &lbrack;Application&amp;rbrack；場合によっては、サムネールが誤ったマテリアルで生成されることがあります
* &lbrack;Captis&amp;rbrack；一部のデバイスでは、高解像度でスキャンを実行すると高さマップが黒くなる
* &lbrack;Captis&rbrack;キャプチャ名が設定されておらず、キャリブレーションが実行されている場合、「キャプチャを開始」ボタンが無効にならない
* &lbrack;Export&rbrack; .sbsar ファイルを書き出すと、ユーザーに通知されずに書き出しが失敗する場合がある
* &lbrack;Filters&amp;rbrack；自動タイリングフィルタの「詳細パラメータ」画面で、パラメータを調整するとフリッカーが発生することがある
* &lbrack;Filters&rbrack;タイリングフィルターのデフォルトパラメーターにより、出力でグレーの斑点が生成される
* &amp;lbrack；フィルター&amp;rbrack；高解像度入力では、「自動タイリング」フィルターの詳細設定で個々のパターンポイントが表示されない場合があります
* &amp;lbrack；フィルター&rbrack;カスタムサイズの自動タイリングパラメーターのパターンサイズのデフォルト値が正しくない
* &amp;lbrack；レイヤー&amp;rbrack；自動タイリングフィルターで発生するカラーの問題が、主に赤いマテリアルで発生
* &amp;lbrack；レイヤー&rbrack;レイヤーを追加すると、一部のツイークがデフォルト値にリセットされる場合があります
* &lbrack;物理サイズを含む物理サイズのサムネールが間違ったHeightスケールを持っている&rbrack;
* &lbrack;UI&rbrack; 表示されるパラメーター名を変更できない
* &lbrack;UI&rbrack;チャンネルアクティベーションボタンが正方形でない
* &lbrack;UI&rbrack;スライダラベルが長すぎると、リセットボタンにアクセスできません
* &lbrack;UI&rbrack; Returnキーを押すかクリックしても、テキストフィールドからフォーカスが削除されない
* &lbrack;UI&amp;rbrack；不要なツールヒントが物理サイズパネルに表示されることがある
* &lbrack;UI&amp;rbrack；空のプロジェクトを作成すると、3Dビューに誤ったメッシュが表示される。
* &lbrack;UI&rbrack;カラーピッカー入力を表示すると、カーソルを合わせたときにラベルが消える
* &lbrack;UI&rbrack;パラメーターを表示するときに、カラードットが正しく配置されない場合がある

### **5.1.0イルフロッタンテ**

*（リリース：2025年8月7日）*

**追加：**

* &lbrack;2D ビュー&rbrack;ブラシサイズが現在のテクスチャ解像度に適応するようになりました
* &lbrack;3D ビュー&amp;rbrack；環境設定で3Dレンダリングのネイティブ表示スケールを切り替え
* &lbrack;Application&rbrack; レンダリングエンジンの更新
* &lbrack;Captis&rbrack;プレビュー中に「四角形にする」可能性を追加
* &lbrack;Captis&amp;rbrack；自動物理サイズ検出
* &lbrack;Captis&amp;rbrack；新しいアセットをキャプチャすると、新しいマテリアルが作成される
* &lbrack;Captis&amp;rbrack；最大面積のピクセル解像度ではなく、ドロップダウンでの解像度の選択をインチ単位またはセンチメートル単位に変更
* &lbrack;Captis&rbrack; アラインメント調整のコンテキストヘルプ
* &lbrack;Captis&rbrack; ラフネスマップを生成
* &lbrack;Captis&rbrack;デフォルトの調整ファイルが見つからない場合にユーザーに警告する
* &amp;lbrack；フィルター&amp;rbrack；構造化マテリアルおよびスキャン用の自動タイリングフィルター
* &amp;lbrack；フィルタ&amp;rbrack；新しい折り曲げ除去フィルタ
* &amp;lbrack；フィルター&rbrack;クローンスタンプフィルター内の新機能
* &amp;lbrack；フィルター&amp;rbrack；イコライズフィルター内の新機能
* &amp;lbrack；レイヤー&rbrack;レイヤーを統合する機能
* レイヤーを右クリックしてレイヤーの名前を変更、複製、削除、または統合を行う場合の&amp;lbrack；レイヤー&rbrack;コンテキストメニュー
* &lbrack;Onboarding&rbrack; Update Welcome and What&#39;s New screens content
* &amp;lbrack；パフォーマンス&amp;rbrack；切り抜きフィルター使用時のパフォーマンス向上
* &lbrack;Performance&rbrack; 3D ビューのメモリ使用量を改善する
* &amp;lbrack；パフォーマンス&rbrack; 3Dビューの更新がより迅速になりました
* &lbrack;物理サイズ&rbrack;物理サイズが有効な場合、Substanceフィルターを操作すると「物理比で表示」が有効になる
* &lbrack;物理サイズ&amp;rbrack；空のスタックに画像を読み込む場合は、画像比に一貫性のある解像度を提案します
* &amp;lbrack；クイックアクション&rbrack;スキャン処理用の3つの新しいクイックアクション
* &amp;lbrack；レイヤーを統合するためのスクリプト&rbrack; API
* &lbrack;Scripting&amp;rbrack；画像読み込みレイヤーの各画像のファイル名を取得する
* &amp;lbrack；スクリプト&rbrack;アセットの特定のチャンネルを有効/無効にする新しい機能
* &lbrack;UI&amp;rbrack；新機能に対応するために、レイヤーパネルのアイコンとボタンをリワークする
* &lbrack;UI&rbrack; 環境光オーサリングの廃止について警告する

**修正済み：**

* &lbrack;2D ビュー&rbrack;Substanceフィルターを使用する場合、「物理比で表示」が機能しない場合がある
* &lbrack;3D キャプチャ&rbrack; Svgファイルがファイルピッカーにリストされていますが、サポートされていません。
* &lbrack;3D ビュー&rbrack; シェーダー設定の放射強度パラメータが機能しない
* &lbrack;3D ビュー&amp;rbrack；新しいアセットの作成時に、メッシュの位置が正しくない場合がある
* &lbrack;3D ビュー&rbrack;サポートされていないハードウェアでパストレーシングレンダリングクラッシュに切り替える
* &lbrack;Application&rbrack;サイズを設定せずに手動メジャーポップアップを閉じると、アプリケーションがハングします
* &lbrack;Application&rbrack; クラッシュ
* &lbrack;Application&rbrack; Windowsでデスクトップを表示するとフリーズする（Windowsキー+ Dキーボードショートカット）
* &lbrack;Application&amp;rbrack；言語切り替え時に起こりうるクラッシュ
* プレビューデータが無効な場合に&lbrack;Captis&rbrack; クラッシュが発生します。
* &lbrack;Captis&rbrack;ズームイン後に完全にズームアウトできない
* &lbrack;Captis&amp;rbrack；一部のウィザードステップでローカリゼーションが見つかりません
* &lbrack;Captis&rbrack; Captisの使用時に終了時にクラッシュする可能性がある
* &lbrack;Captis&rbrack;デバイスに調整ファイルがない場合、スキャンが機能しない
* &amp;lbrack；フィルター&rbrack; クローンスタンプフィルターを使用した場合のブラシプレビューが、テクスチャとブラシサイズによっては正しくない場合があります
* &amp;lbrack；フィルター&rbrack;アップスケールフィルター使用後の誤った出力サイズ
* &amp;lbrack；フィルター&amp;rbrack；環境の回転およびスタイル設定フィルターのアイコンが表示されない
* &amp;lbrack；フィルター&amp;rbrack；一部のフィルターを更新すると、正しくレンダリングされない可能性があります
* &amp;lbrack；レイヤー&rbrack; 2つのマテリアルをブレンドすると、最初のレンダリングが正しく行われない
* &lbrack;Layers&rbrack;レイヤを更新するボタンは、更新が1つしかない場合でも「すべて更新」と表示される
* &amp;lbrack；レイヤー&rbrack; レイヤースタックに画像を読み込む際の不要な計算
* &lbrack;Performance&rbrack; 法線マップ形式処理を改善してレンダリング時間を短縮
* &lbrack;物理サイズ&amp;rbrack；手動測定ポップアップは、自動測定を実行した後にのみ機能します。
* &lbrack;物理サイズ&rbrack;物理サイズが有効な場合に、書き出しポップアップで間違った書き出し解像度が表示される
* &amp;lbrack；クイックアクション&amp;rbrack；生成されたアセット名にローカリゼーションがありません
* &lbrack;UI&rbrack; Asset preview on hover may not show
* &lbrack;UI&rbrack; [既定値にリセット]ボタンをクリックすると、コントロールの一部が壊れる場合があります
* &lbrack;UI&rbrack;プロジェクトの切り替え時にエラーメッセージがクリアされない(&amp;l)
* &lbrack;UI&rbrack;アセットがない場合、ビューポートとプロパティパネルのマテリアル名が空であることを確認
* &lbrack;UI&rbrack; [視点]パラメータの[既定値にリセット]ボタンが機能しない
* &lbrack;UI&rbrack;デフォルト値にリセットボタンのオーバーラップ
* &lbrack;UI&rbrack;パネルがドッキング解除されていると、一部のボタンがクリックできない
* &lbrack;UI&rbrack;テクスチャタイリングVパラメータがビューア設定と3Dビューで部分的に非表示になる

**削除済み：**

* &lbrack;3D キャプチャ&rbrack; 3D キャプチャサポートを削除
* &lbrack;Application&rbrack; macOS x86サポートを削除

### **5.0.3ヘーゼルナッツ**

*（リリース：2025年6月3日）*

**追加：**

* &lbrack;Captis&rbrack; マテリアルに既存の名前と同じ名前を付ける
* &lbrack;Captis&rbrack;エラーメッセージをトーストではなくポップアップに移動
* &amp;lbrack；フィルター&amp;rbrack；刺繍を更新
* &lbrack;Preferences&rbrack; Add reset in viewer settings and shaders settings
* &lbrack;UI&rbrack;プロジェクトのアセットに「場所を表示」メニュー項目を表示しない

**修正済み：**

* &lbrack;3D キャプチャ&rbrack; メッシュの後処理フィルタが予期したマップを出力しない
* &lbrack;3D ビュー&rbrack; 3Dビューが、シェーダーキャッシュの破損により機能しない
* &lbrack;3D ビュー&rbrack;シーンがZ-upの場合、グリッドとグリッドは垂直です。
* &lbrack;3D ビュー&rbrack; メッシュが消えることがある
* &lbrack;Application&rbrack;ログインせずに起動時にログインウィンドウを閉じると、アプリケーションがクラッシュになることがある
* プラグイン設定ファイルへのアクセスが拒否された場合の&lbrack;Application&rbrack; クラッシュ
* &lbrack;Application&amp;rbrack；現在のマテリアルは、プロジェクトの保存時に選択解除されます。
* &amp;lbrack；アプリケーション&rbrack;デフォルトレイアウトにリセットすると、解像度が64x64に設定される
* &lbrack;Application&rbrack; Samplerでレイヤースタックのレンダリングにクラッシュすることがある
* &amp;lbrack；書き出し&amp;rbrack；書き出し解像度が64x64にリセットされることがある
* &lbrack;Export&rbrack; .sbs/.sbsarファイルをエクスポートできない場合があります
* &lbrack;Layers&rbrack; 「ベースマテリアルを追加」ボタンが空の場合、何も実行されない
* &lbrack;Layers&rbrack; マテリアルの複製時にテクスチャタイリングが変更される
* 物理サイズパネルが画像の読み込み前にドッキングされていた場合、&lbrack;物理サイズ&amp;rbrack；自動測定が機能しない
* &lbrack;Scripting&amp;rbrack；自動保存プラグインが壊れている
* &lbrack;UI&amp;rbrack；書き出しダイアログの間隔が正しくない
* &lbrack;UI&rbrack;ツイークのスライダアニメーションが機能しない
* &lbrack;UI&rbrack;スライダーが必要に応じて整数値にスナップされない
* &lbrack;UI&amp;rbrack；一部のドロップダウンメニューがトリミングされる

### **5.0.2ヘーゼルナッツ**

*（リリース：2025年4月22日）*

**修正済み：**

* &lbrack;Application&rbrack; Back button on the Homepage is broken
* 破損したデータが以前のバージョンからディスクに存在する場合、Samplerが起動しないことがある(&lbrack;Application&rbrack;)
* &lbrack;Application&amp;rbrack；読み込まれた画像がビューポートまたはレイヤースタックに表示されません
* &lbrack;Captis&rbrack; Captis IPアドレスフィールドが、Samplerの再起動後も空のままになる
* &lbrack;Captis&rbrack;ライブカメラプレビューは、アプリケーションの言語が英語に設定されている場合にのみ機能します
* &amp;lbrack；書き出し中に書き出し&rbrack;クラッシュ&amp;lbrack；レイヤー&amp;rbrack；の描画が、以前に保存したプロジェクトで機能しないことがある
* &lbrack;Layers&rbrack; Samplerは、1つのチャンネルのみが更新されると、すべてのテクスチャを更新することがあります。
* &lbrack;Layers&rbrack; 5.0.xにアップグレードした後、レイヤースタックでマテリアルブレンドを使用できない
* &lbrack;Layers&amp;rbrack；以前のバージョンのImage to Image (AI)でプロジェクトを更新すると、マテリアルがすべて黒くなるマテリアル
* &lbrack;Layers&rbrack;サポートされていない画像を読み込もうとすると、Samplerが壊れたレイヤーを作成する
* &lbrack;Scripting&rbrack; Python APIの一部が空のプロジェクトでは機能しません
* &lbrack;UI&rbrack;メニュー項目がファイルメニューでオーバーフローすることがある

### **5.0.1ヘーゼルナッツ**

*（リリース：2025年3月20日）*

**追加済み**

* &amp;lbrack；アプリケーション&amp;rbrack；更新されたグラフィックドライバーの互換性リスト
* &lbrack;Captis&rbrack;オペレーティングシステムポリシーによってHP Z Captisの使用がブロックされた場合にポップアップを表示
* &amp;lbrack；クイックアクション&rbrack;ツールチップでクイックアクションが無効になっている理由を説明する
* &lbrack;UI&rbrack; クラッシュレポートウィンドウのUIスタイル設定
* &lbrack;UI&rbrack;クリップボードにコピーする際に、トーストを表示して完了を通知

**修正済み：**

* &lbrack;2D View&rbrack;球面投影法がオフの場合、露光量スライダーは効果がありません
* &lbrack;2D View&rbrack;テクスチャの外側をペイントすると、ストロークが途切れる(&amp;r)
* &lbrack;2Dビュー&amp;rbrack；露出ボタンにツールチップがありません。
* &lbrack;2Dビュー&amp;rbrack；正方形でないイメージの側面のズームがマウスに従わない
* &lbrack;3D キャプチャ&rbrack; 3D キャプチャがWindows 11 24H2で機能しない
* &lbrack;メッシュ再構築段階でSamplerを終了した場合の3D キャプチャ&rbrack; クラッシュ
* &lbrack;3Dビュー&amp;rbrack；計算時間が0ミリ秒と表示される場合がある
* &lbrack;3Dビュー&amp;rbrack；直交投影からパース投影に変更すると、ビューポートがグレーになる
* &amp;lbrack；アプリケーション&rbrack; GPU機能をチェックすると起動時にクラッシュする
* &lbrack;Application&rbrack;インストール中にクラッシュする
* &amp;lbrack；メタデータフィールドを右クリックすると、終了時にアプリケーション&amp;rbrack；がクラッシュする
* &amp;lbrack；オペレーティングシステムのファイルエクスプローラーからSBSARを開くと、アプリケーション&amp;rbrack；環境ライトが消える
* &lbrack;Application&rbrack; Samplerの実行中に.sbsarを開くと、「テクスチャ分割」設定が変更される
* &lbrack;Captis&amp;rbrack；一部のメタデータがキャプチャステップ間で転送されない可能性があります
* &lbrack;Captis&amp;rbrack；作成されたアセットの名前がメタデータフィールドに入力されたものではありません
* &lbrack;Content&rbrack;サンプルプロジェクトはフィルターの更新を求められますが、すでに最新の状態です
* &amp;lbrack；フィルター&amp;rbrack；通常/Height調整フィルターにアイコンがありません
* &lbrack;Layers&rbrack;イメージインポートレイヤのイメージを変更できません
* &lbrack;Layers&rbrack; クラッシュ（アップスケールフィルター使用時）
* &lbrack;Layers&amp;rbrack；古い画像をマテリアルに更新すると、マテリアルがすべて黒くなる
* &amp;lbrack；レンダリング&rbrack;アセットを作成した直後にレイヤースタックを微調整すると、レンダリングが壊れる
* &lbrack;Scripting&rbrack;プロジェクトにアセットがない場合の自動保存プラグインクラッシュ
* &lbrack;Tools&rbrack;ブラシツールバーにブラシサイズの値が表示されない
* &lbrack;UI&rbrack;アプリケーション言語を変更しても、ホーム画面の一部のラベルが更新されない
* &lbrack;UI&rbrack;スライダーテキストフィールドでEscキーまたはEnterキーを押しても、フォーカスが失われません
* &lbrack;UI&rbrack;プロパティパネルで、「すべてをリセット」ボタンとアセット名のラベルが重なっています
* &lbrack;UI&rbrack;パネルのドッキングおよびドッキング解除時の問題
* &lbrack;UI&rbrack;オーバーレイパネルでのスクロールは、下のウィンドウでもスクロールされます。
* &lbrack;UI&rbrack;ホーム画面の「最近使用したプロジェクト」セクションで、リストビューに切り替えが機能しない
* &lbrack;UI&rbrack; ビューポート表示モードボタンアイコンは常に2D/3Dを表示

### **5.0.0ヘーゼルナッツ**

*（リリース：2025年2月20日）*

**追加済み**

* &lbrack;Onboarding&amp;rbrack；学習コンテンツ、サンプルプロジェクト、クイックアクション、最近のプロジェクトにすばやくアクセスできる新しいホームページ。
* &amp;lbrack；オンボーディング&amp;rbrack；ホームページおよび専用パネルからアクセスできる新しいクイックアクションを使用して、すばやく作業を開始できます
* &lbrack;Onboarding&rbrack; &lbrack;Content&rbrack; Quick Actionsは、最もよく使用されるレイヤーをレイヤースタックに取り込む定義済みのワークフローです
* &lbrack;Onboarding&amp;rbrack；新しいクイックスタートメニュー、クイックアクション、またはカスタムプロジェクトを介して新しいプロジェクトを作成する可能性
* &lbrack;Onboarding&amp;rbrack；専用ボタンを介してホームページから直接、空のプロジェクトを作成する可能性
* &lbrack;3D ビュー&amp;rbrack；新しい高度なラスタライザおよびパストレーサにより、Substanceエコシステム全体で新しいレンダリング機能（コーティング、光沢、translucency、表面化散乱などのプロパティ）と視覚的な一貫性を実現
* &lbrack;3D ビュー&rbrack;ビューア設定に3Dビューから直接アクセスできるようになりました
* &lbrack;3D ビュー&rbrack;レンダリングスナップショットをクリップボードまたはファイルに保存する可能性
* &lbrack;3D ビュー&rbrack; グリッドを表示してシーンの原点を表示
* &lbrack;3D ビュー&amp;rbrack；地表プレーンがシャドウとリフレクションをキャッチできるようにします
* &lbrack;3D ビュー&amp;rbrack；地表プレーンの反射と不透明の度合いを制御する
* &lbrack;3D キャプチャ&amp;rbrack；地面にメッシュを配置
* &lbrack;Application&rbrack;アプリケーションの起動時にハードウェアの互換性を確認
* &lbrack;Application&rbrack; クラッシュレポートウィンドウが、クラッシュが発生した直後に開くようになりました
* &lbrack;Content&rbrack;サンプルプロジェクトを開いて簡単に開始
* &amp;lbrack；書き出し&rbrack; USDファイルのAdobe Standard Materialシェーダーの書き出し
* &lbrack;Generative AI&amp;rbrack；画像からテクスチャへの入力ワークフローで画像を使用する際に「推測しない」タグをチェックする
* &amp;lbrack；プロジェクト&rbrack;サムネールは、プロジェクトをすばやく開くためにプロジェクトファイル内に保存されます
* &amp;lbrack；プロジェクトファイル内にキャッシュデータを保存するための環境設定の設定(&lbrack;Project&rbrack;)。異なるモード（キャッシュなし、ライトキャッシュ、フルキャッシュ）
* &amp;lbrack；スクリプト&rbrack; &amp;lbrack；変更の解除&rbrack; QtのQt 6.15への移行 – 既存のプラグインの互換性に影響を与える
* &lbrack;Scripting&rbrack;デフォルトのプラグインとスクリプトフォルダーがDocumentsフォルダーに追加されました
* &lbrack;Scripting&rbrack;メインのSamplerパネルと視覚的に一貫性のあるプラグイン用の新しいUI
* &lbrack;Scripting&rbrack; Access 2プラグインの例 – Samplerプラグインの機能を検出
* &amp;lbrack；スクリプト&amp;rbrack；新しいopen_3d_catpure()関数
* &lbrack;Scripting&rbrack;レイヤーを挿入する際に、ターゲット位置の上または下に挿入するかどうかを制御

**修正済み：**

* macOSでオブジェクトキャプチャを開始できない場合に&lbrack;3D キャプチャ&rbrack;クラッシュが発生する
* &lbrack;Application&rbrack; クラッシュ at exit
* &lbrack;Application&rbrack;アセットをプロジェクトパネルに追加する際に終了時にハングする
* &lbrack;Application&rbrack;プロジェクトアセットの名前を変更すると、Enterキーを押さない限り機能しない
* &lbrack;Application&rbrack; 「元に戻す」および「やり直し」メニュー項目は、必要なときに無効になりません。
* &amp;lbrack；アセット&rbrack;アセットパネルの「すべてのライブラリ」セクションからアセットを削除できない
* &lbrack;Content&rbrack; Atlas creator – 既存の不透明度マップを使用（存在する場合）
* &lbrack;Content&rbrack; Color ID ブレンド – ベースカラーのカラー選択を修正
* &lbrack;Layers&rbrack;ジェネレータ使用時の無駄な計算を避ける
* &amp;lbrack；画層&rbrack;ジェネレータをツイークすると、過度に多くの計算がトリガされる場合があります
* &amp;lbrack；パフォーマンス&rbrack; GPUメモリ管理の改善
* &lbrack;Performance&rbrack;レンダーキャッシュは、アプリの再起動時に使用できない場合があります
* &amp;lbrack；リソース&amp;rbrack；読み取り専用ファイルがアセットパネルに表示されない
* &lbrack;Scripting&rbrack;レイヤーを別のレイヤーに追加した後、再利用できるようにする
* &lbrack;Scripting&rbrack; 1つのスクリプトでレイヤースタック構造を数回変更すると失敗することがある

**削除済み：**

* &lbrack;Application&rbrack; .dngおよび.nef画像ファイルのサポートを削除

## バージョン4

### **4.5.2グリュイエール**

*（リリース： 2024年11月7日）*

**修正済み：**

* &amp;lbrack；コンテンツ&amp;rbrack；切り抜き、刺繍、Heightブレンドフィルター

### **4.5.1グリュイエール**

*（リリース：2024年7月30日）*

**修正済み：**

* &amp;lbrack；レイヤー&amp;rbrack；グレースケールマスクの描画が機能せず、クローンスタンプ、ペイントワープ、コンテンツに応じた塗りつぶしなどのツールに影響を与える

### **4.5.0グリュイエール**

*（リリース：2024年7月18日）*

**追加済み**

* &amp;lbrack；相互運用性&rbrack; UE5、Blender、Maya、3DsMax Unityにマテリアルを送信
* &lbrack;Content&amp;rbrack；新しいテクスチャジェネレータカテゴリ – グラデーション
* &lbrack;Content&rbrack; HDRI ツール – 新しいEnvironment rotation filter

**修正済み：**

* &lbrack;表示されるパラメーター&rbrack; .sbsar入力値の表示が機能しない
* &amp;lbrack；レイヤー&rbrack;Base colorがグレースケール画像で赤に変わる
* &amp;lbrack；カラーチャンネルで使用されているレンダリング&rbrack; グレースケールイメージのカラースペースが正しくありません
* &amp;lbrack；スクリプト&amp;rbrack；書き出しプリセットを使用すると、予期したチャンネルが書き出されない場合がある
* &amp;lbrack；コンテンツ&rbrack;Dirt – 画像の上にDirtフィルターをマテリアルに適用すると、黒の法線が生成される
* &lbrack;Content&rbrack; エンボス - エンボスフィルタのパターンのスケーリングが0 ～ 1の間で線形ではありません
* &lbrack;Content&rbrack; Make it tile – 標準とHeightの一貫性を向上

### **4.4.1フォントの種類**

*（リリース：2024年6月6日）*

**修正済み：**

* &lbrack;Content&rbrack;Dirtフィルタがありません
* &lbrack;Generative AI&rbrack; Network error occurrently when using Image to Image to テクスチャ

### **4.4.0フォントの期限**

*（リリース：2024年5月23日）*

**追加：**

* &lbrack;Application&rbrack; 3D キャプチャキャッシュが別のサブフォルダに格納されるようになりました
* &lbrack;Generative AI&amp;rbrack；画像をテクスチャに変換（ベータ版）
* &amp;lbrack；ジェネレーティブAI&rbrack;テキストをパターン化（ベータ版）
* &amp;lbrack；ジェネレーティブAI&rbrack;テキストからテクスチャ （ベータ版）
* &lbrack;Scripting&rbrack;アセットに「resource」プロパティが追加されました
* &lbrack;Scripting&rbrack;レイヤーに&#39;output_usages&#39;プロパティが追加されました

**修正済み：**

* &amp;lbrack；破損したプロジェクトファイルを開くときのアプリケーション&rbrack; クラッシュ
* &lbrack;Application&rbrack;プロジェクトに破損したアセットが含まれている場合のクラッシュ
* &lbrack;Windowsでモニターのプラグを抜く際のApplication&rbrack; クラッシュ
* &lbrack;Application&rbrack; Windowsタスクバーのアプリケーションアイコンが正しくない
* &lbrack;Application&rbrack;メイン設定ファイルが破損すると、ファイルが削除される可能性があります
* &lbrack;Application&rbrack;パネルがポップアップの前に表示されます
* &lbrack;Content&rbrack; テクスチャジェネレータのサムネイルがぼやけている
* &lbrack;Export&amp;rbrack；読み込まれた画像から生成された不透明度チャンネルが.sbs/.sbsarの書き出し時に破損する
* &lbrack;Filters&rbrack; Upscaleは、入力レイヤーに応じてクラッシュする場合があります
* &lbrack;Generative AI&rbrack;サービスから予期しない結果を受け取った場合に起こりうるクラッシュ
* &amp;lbrack；環境変数からプラグインを自動読み込みする際のスクリプト&rbrack; クラッシュ
* &lbrack;Scripting&rbrack; APIを使用して出力使用を割り当てる際に考えられるクラッシュ

### **4.3.3エンパナーダ**

*（リリース：2024年3月26日）*

**追加：**

* &lbrack;3D キャプチャ&amp;rbrack；後処理時の新しい高度な自動UVパラメーター
* &lbrack;Filters&rbrack; Perforate filter:カスタムパターンの反転およびサイズ変更の機能

**修正済み：**

* macOSで&lbrack;3D キャプチャ&amp;rbrack；のBase colorが正しくない可能性がある
* &amp;lbrack；新しいバージョンを処理する際の3D キャプチャ&rbrack; クラッシュ
* macOSで&lbrack;3D キャプチャ&amp;rbrack；後処理ステップがクラッシュすることがある
* &lbrack;3D キャプチャ&rbrack; メッシュ変形レイヤーが正しくレンダリングされない可能性がある
* 以前のインスタンスがまだ書き出し中の状態でSamplerを起動すると、&lbrack;Application&rbrack; クラッシュが発生します。
* &lbrack;Application&rbrack; Samplerが初めて起動されたとき、しばらく応答しない
* &lbrack;Export&rbrack;Anisotropy angleマップが書き出されない
* &amp;lbrack；フィルター&amp;rbrack；布地の織りをレイヤースタックに追加するとクラッシュが発生する場合がある
* &amp;lbrack；フィルター&rbrack; レイヤースタックにエンボスを追加すると、クラッシュが発生する可能性があります
* &lbrack;32 bit画像を使用している場合のフィルター&rbrack;コンテンツに応じた塗りつぶしのクラッシュ
* &amp;lbrack；フィルター&rbrack; エンボス：下のレイヤーの不透明度が完全にオーバーライドされていない
* &lbrack;Filters&rbrack; Fill: DesignerとPainterで描画モードが機能しない
* &amp;lbrack；フィルター&amp;rbrack；刺繍：自動カラー選択が壊れています
* &lbrack;Preferences&rbrack; 3D キャプチャキャッシュにサポートされていないパスを設定できないようにする
* &lbrack;Preferences&rbrack; The Normal Format preference does not work
* &lbrack;Scripting&rbrack; Asset.export_materialのchannelsパラメータでは、大文字と小文字が区別されます

### **4.3.2エンパナーダ**

*（リリース：2024年2月22日）*

**修正済み：**

* &amp;lbrack；アプリケーション&rbrack; Windows上のネットワーク共有にプロジェクトを保存すると、プロジェクトファイルが破損する

### **4.3.1エンパナーダ**

*（リリース：2024年2月15日）*

**修正済み：**

* &lbrack;3D キャプチャ&rbrack;マスクのバッチ生成中に画像ファイルにアクセスできなくなるとクラッシュする
* &lbrack;Export&amp;rbrack；切り抜きまたは入力ポリシーレイヤーに対する相対を使用してマテリアルを書き出すと、無効な結果が生じる
* &amp;lbrack；レイヤー&rbrack;レイヤースタックのレンダリング中にクラッシュすることがある
* &lbrack;Filters&rbrack;Embroidery - MacOSでマテリアル入力を使用する際の問題を修正
* &amp;lbrack；フィルター&rbrack;スタイル化 – テクスチャジェネレーターのサポート
* &lbrack;Filters&rbrack; Pattern – パラメータ名を修正
* &lbrack;Localization&rbrack; &quot;名前を付けて保存…&quot; ハードウェア情報ウィンドウのヘルプメニューがローカライズされていない

### **4.3.0エンパナーダ**

*（リリース：2024年1月25日）*

**追加済み**

* &amp;lbrack；アセット&amp;rbrack；新しいアセットタイプ：テクスチャジェネレータ
* &amp;lbrack；アセット&rbrack;スターターアセットに含まれる新しいマテリアル
* &lbrack;Assets&rbrack;プロパティパネルの画像パラメーター用の新しいアセットピッカー
* &lbrack;Assets&rbrack;アセットパネルからプロパティパネルの画像ピッカーに、テクスチャジェネレーターをドラッグ&amp;ドロップ
* &lbrack;Assets&rbrack;オペレーティングシステムのファイルエクスプローラーからテクスチャジェネレータをドラッグアンドドロップ
* &lbrack;Assets&rbrack; Filtersは、画像入力のユーザータグを介してフィッティングジェネレータを提案できます
* &amp;lbrack；アセット&rbrack; テクスチャジェネレータは、ユーザタグを使用してどのフィルタを提案するかを定義できます。
* &amp;lbrack；コンテンツ&amp;rbrack；新しい遠近法切り抜きフィルター
* &lbrack;Content&rbrack; New Stylization filter
* &amp;lbrack；コンテンツ&amp;rbrack；塗りつぶしフィルターの描画モード
* &lbrack;Content&amp;rbrack；更新された刺繍フィルター
* &lbrack;Content&amp;rbrack；更新されたペイントラップフィルター
* &lbrack;Content&amp;rbrack；すべてのフィルタがテクスチャジェネレータをサポートするように更新されました
* &lbrack;Layers&rbrack; レイヤースタックにテクスチャジェネレータ出力チャンネルを追加する際に、出力チャンネルを選択する機能
* &lbrack;Layers&rbrack; テクスチャジェネレータでプリセットを簡単に一覧表示して適用する機能
* &lbrack;Layers&rbrack; テクスチャジェネレータのプレビューをイメージピッカーに表示する
* &amp;lbrack；画層&rbrack; テクスチャジェネレータパラメータを表示および書き出し可能
* &lbrack;Layers&rbrack; テクスチャ Import Creation Templateを使用して1枚の画像を読み込むときに、Base color使用量を割り当てる
* プロパティパネルの画像ピッカーで、互換性のないファイルをドラッグ&amp;ドロップしようとすると、&amp;lbrack；レイヤー&rbrack;フィードバックが表示されます。
* &lbrack;Layers&amp;rbrack；読み込んだイメージのアルファチャンネルから不透明度チャンネルを生成する
* &lbrack;Layers&rbrack; Image to Category (AI)は、マテリアルを変更する際の計算速度が速くなります。
* &amp;lbrack；レイヤー&amp;rbrack；作成テンプレートの使用後に最も関連性の高いレイヤーを選択
* &amp;lbrack；レイヤー&amp;rbrack；位置ウィジェットを「詳細パラメーター」グループのスライダーで微調整できるようになりました
* &lbrack;Export&rbrack;キューに未加工の数字の代わりにパーセンテージを表示
* &lbrack;Interoperability&amp;rbrack；不透明度チャンネルが、Painterへの送信時にアルファチャンネルとして認識されるようになりました。
* &amp;lbrack；アプリケーション&rbrack;ハードウェア情報を表示および保存するための新しいダイアログ
* &lbrack;Application&amp;rbrack；各プロジェクトのデフォルトのHeightスケールを変更する新しい環境設定
* &lbrack;Application&amp;rbrack；古いアセットの表示方法を改善
* &lbrack;Scripting&amp;rbrack；新しいasset.documentResolution()およびasset.setDocumentResolution()関数
* &amp;lbrack；スクリプト&amp;rbrack；新しいselect_asset()関数
* &lbrack;Scripting&rbrack; Python API for Texture Generators
* &lbrack;Scripting&rbrack; get_project_assets()が3Dオブジェクトを返すようになりました
* &lbrack;UI&rbrack;アセットのサムネールサイズはアセットパネルで変更可能
* &lbrack;UI&amp;rbrack；更新されたビューポート表示アイコン

**修正済み：**

* &lbrack;2D View&rbrack;マウスホイールによるズームが244%でブロックされる
* &amp;lbrack；アプリケーション&rbrack;グラフィックAPIの初期化時に起動時にクラッシュする
* &lbrack;Application&rbrack;プロジェクト名に#文字が含まれているとクラッシュする
* &lbrack;Application&amp;rbrack；古いプロジェクトを開くとクラッシュする可能性がある
* &lbrack;Application&amp;rbrack；現在のプロジェクトを再度開くと、クラッシュする可能性があります
* &lbrack;Application&amp;rbrack；一部のプロジェクト変更が登録されず、保存されていない場合にプロジェクトを閉じると警告なしに失われます
* &lbrack;Export&rbrack; .sbs/.sbsar同じ名前のファイルを複数使用した場合の書き出しに関する問題
* &lbrack;Export&amp;rbrack；書き出したグレースケールイメージの.sbs/.sbsarファイルのカラースペースが正しくありません
* &amp;lbrack；フィルター&amp;rbrack；不透明度ブレンドの動作の問題
* &lbrack;Layers&rbrack; .svgファイルが正しい解像度でレンダリングされないことがある
* &lbrack;Performance&rbrack;ディスクに保存する必要がないプロジェクトもあります
* &amp;lbrack；プロジェクト&amp;rbrack；古いプロジェクトを読み込むと、関連付けられたプリセットが読み込まれない
* &lbrack;Scripting&amp;rbrack；最初に挿入されたレイヤーのパラメーターを取得できません
* &lbrack;UI&rbrack;アセットのカーソルを合わせたときに表示されるプレビューポップアップが、間違った場所や画面に表示されることがある
* &lbrack;UI&amp;rbrack；ドッキングされていないパネルは、スタートアップスクリーンの上に表示されて使用できます。

### **4.2.2どら焼き**

*（リリース：2023年12月5日）*

**追加：**

* &lbrack;3D キャプチャ&rbrack; 3D キャプチャがWindowsで5% ～ 10%高速になりました
* &lbrack;3D キャプチャ&rbrack;デシメーション前のメッシュクリーンアップを改善する
* &lbrack;エンジン&rbrack; Substance engineをバージョン9.0.3にアップデート
* &lbrack;Layers&rbrack; Content-Aware Fill:アップストリームの更新、さまざまなユースケースの修正、Linuxのサポート

**修正済み：**

* &lbrack;3D キャプチャ&rbrack;アラインメント後に「戻る」をクリックしてから「次へ」をクリックしても、点群が更新されない
* &lbrack;3D キャプチャ&rbrack; メッシュがプロジェクトに追加された後、穴が表示される(&rbrack;)
* &lbrack;3D キャプチャ後にフルスクリーンモードを終了すると、Application&rbrack; クラッシュが発生します。
* &lbrack;Application&rbrack; クラッシュと巧妙に細工された画像ファイル
* &lbrack;Application&rbrack; Samplerを終了するときに「すべてのライブラリ」に保存すると、再起動時にアセットパネルが空になる
* &lbrack;Application&rbrack; マテリアルを書き出すときのメモリリーク
* &lbrack;Application&amp;rbrack；以前のバージョンのSamplerで保存したプロジェクトを開くと、クラッシュが発生する場合がある
* &lbrack;Application&rbrack; 3D メッシュの変換に失敗した場合の潜在的なクラッシュ
* &lbrack;Application&rbrack; Samplerの実行中に.sbsarを開くと、サイレントクラッシュが発生する
* &amp;lbrack；カスタム使用で.sbs/.sbsar ファイルを書き出すときに書き出し&rbrack; クラッシュが発生する
* &lbrack;Export&amp;rbrack；書き出された法線マップは、ユーザ設定に関係なく常にDirectXになります。
* &lbrack;Export&rbrack; macosで3DオブジェクトをFBXファイルに書き出すことができない
* &lbrack;Export&rbrack;sbsar ファイルフィルターを.sbs/.embroideryとして含むレイヤースタックを書き出す際の不一致
* &lbrack;Export&rbrack; .sbs/.sbsarファイルの書き出しが機能しない場合がある
* &lbrack;Export&rbrack; .sbs/.sbsar ファイル画像を書き出すときに適切なビット深度が指定されない場合がある
* &amp;lbrack；レイヤー&rbrack;スプラッタのレイヤーを非表示にすると、最初の子レイヤーがレンダリングされる
* &amp;lbrack；レイヤー&rbrack;マスクを明るさ/コントラストレイヤーに読み込むときにクラッシュが発生する
* &lbrack;Layers&rbrack;レイヤーを削除した後、誤解を招くエラーメッセージが表示される
* &amp;lbrack；レイヤー&rbrack;アセットをダウングレードする際に起こりうるクラッシュ
* &amp;lbrack；レイヤー&amp;rbrack；一部の出力は、チャンネル設定パネルで使用を強制しない限り、入力に接続されません
* &lbrack;物理サイズ&amp;rbrack；参照レイヤードロップダウンが誤ってリセットされることがある
* &lbrack;UI&rbrack;テンプレート情報の読み込みアイコンの更新が必要
* &lbrack;UI&rbrack;ビューポートのショートカットヒントは、ビューポートのレイアウトが変わるたびに表示されます

### **4.2.1どら焼き**

*（リリース：2023年9月21日）*

**追加：**

* &lbrack;Content&rbrack; Image to Material – 法線マップのマイクロディテール生成を改善
* &lbrack;Content&rbrack; Image to Material – 新しい描画強度パラメータ
* &lbrack;Layers&amp;rbrack；画像は画像読み込みレイヤーに追加できます
* &amp;lbrack；レイヤー&amp;rbrack；画像は画像読み込みレイヤーで削除可能
* &lbrack;Layers&amp;rbrack；無効なレイヤを削除できるようになりました
* &lbrack;2Dビュー&rbrack;チャンネルを切り替えるためのShift+Cショートカット
* &lbrack;3D キャプチャ&amp;rbrack；読み込む画像が20枚に満たない場合にトースト警告を表示
* &lbrack;Application&amp;rbrack；初期設定のマテリアルテクスチャタイリング値を設定する新しい環境設定
* &lbrack;Onboarding&amp;rbrack；画像からマテリアル(AI)およびアップスケール用の更新されたチュートリアルUI
* &lbrack;Scripting&rbrack; data API: Capture3dStateがalignedに設定されていると、DatasetInfoにより多くの3D キャプチャが含まれます
* &lbrack;Scripting&rbrack;create_asset()への新しいselect_asset引数。 新しい関数： wait_for_computation()およびclear_render_cache()

**修正済み：**

* &amp;lbrack；レイヤー&amp;rbrack；切り抜き領域が非常に小さいときにクラッシュする
* &amp;lbrack；レイヤー&amp;rbrack；切り抜きフィルターを追加または微調整するとクラッシュする
* &amp;lbrack；レイヤー&amp;rbrack；切り抜き領域を正方形にすると、マテリアルの出力解像度が正しくない
* &lbrack;Layers&amp;rbrack；複数のレイヤーが無効になっていると、出力が消えることがある
* &lbrack;Layers&rbrack;レンダーキャッシュが、Image to Material(AI)およびUpscaleフィルターで正しく無効にならない場合がある
* &lbrack;Layers&amp;rbrack；警告ポップアップで「このメッセージを再度表示しない」を選択した場合に、アップスケールフィルターを追加できない
* &amp;lbrack；レイヤー&amp;rbrack；一度変更すると、刺繍フィルターの画像を復元できません
* &amp;lbrack；書き出し&amp;rbrack；法線フォーマットの変更時に書き出された法線マップ解像度が変更される
* &lbrack;Export&amp;rbrack；環境を書き出すときに「\_environment」ファイル名サフィックスを削除する
* &lbrack;Export&rbrack;レイヤースタックにワープ変形レイヤーがある場合、.sbsarファイルを書き出すことができません
* &lbrack;2D View&rbrack; 「画面に合わせる」が、解像度の変更時に機能しない
* &lbrack;Application&amp;rbrack；計算中にアプリケーションウィンドウを閉じた後でも、アプリケーションプロセスが実行中である可能性があります
* &lbrack;Application&amp;rbrack；終了時にクラッシュする
* &amp;lbrack；アプリケーション&rbrack; GPUアクセラレーションニューラルネットワークの切り替え時にレンダーキャッシュを無効にする
* &lbrack;Scripting&rbrack;プラグインに既存のパネル名を付けると、予期しない動作が発生する
* &lbrack;UI&rbrack;ツールチップ付きの項目をクリックすると、再起動するまでツールチップが表示されなくなります。
* &lbrack;UI&rbrack;アセットの切り替え時にHeightスケールの値が変わる場合がある
* &lbrack;UI&rbrack;コンボボックスのマージンが正しくない

### **4.2どら焼き**

*（リリース： 2023年9月5日）*

**追加：**

* &lbrack;Content&rbrack; Image to Material(AI)とDelighterフィルターを大幅に改善
* &lbrack;Content&rbrack; New Upscale filter
* &lbrack;Content&amp;rbrack；切り抜きフィルターにダイナミック出力解像度が追加されました。
* &amp;lbrack；マテリアル作成テンプレート&rbrack;ドキュメントサイズ設定を追加。
* &amp;lbrack；マテリアル作成テンプレート&amp;rbrack；新しい「切り抜きを追加」トグルボタン。
* &lbrack;マテリアル作成テンプレート&amp;rbrack；新規「マテリアルをアップスケール」トグル
* &amp;lbrack；マテリアル作成テンプレート&amp;rbrack；読み込まれたイメージサイズを表示
* &amp;lbrack；マテリアル作成テンプレート&amp;rbrack；読み込まれた画像が使用できない場合にフィードバックを提供
* &amp;lbrack；マテリアル作成テンプレート&amp;rbrack；画像サイズに一貫性がない場合に警告
* &amp;lbrack；マテリアル作成テンプレート&amp;rbrack；新しい警告とツールチップ
* &lbrack;Layers&rbrack;レイヤスタックのレイヤの解像度を表示します。
* &lbrack;Layers&rbrack; Layer compute resolutionがDocument sizeまたはInput sizeに設定できるようになりました。
* &amp;lbrack；レイヤー&rbrack;レイヤースタックのレイヤー解像度を表示
* &lbrack;Layers&rbrack;レイヤ解像度ポリシーをDocumentまたはLayer Inputに切り替える（該当する場合）
* &lbrack;Layers&rbrack;アップスケールフィルターが手動で追加されたときにユーザーに警告し、いくつかのドキュメントを提供する
* &lbrack;Layers&amp;rbrack；線形アップスケールを行う際にユーザーに警告し、代わりにアップスケールフィルターの使用を提案します
* &lbrack;Layers&rbrack; Computing an Image to Material (AI) layerは、レイヤースタックを微調整する際のレンダリング時間を短縮するために、より迅速にキャンセルできるようになりました。
* &lbrack;Layers&rbrack; Computing an Upscale layerを高速にキャンセルして、レイヤースタックを微調整するときのレンダリング時間を短縮できるようになりました
* &amp;lbrack；書き出し&amp;rbrack；書き出したテクスチャの解像度を上書きします
* &amp;lbrack；書き出し&rbrack;リストを書き出すチャンネルがソートされました
* &amp;lbrack；書き出し&amp;rbrack；書き出すチャンネルリストにチャンネル解像度を表示する
* &lbrack;Application&rbrack; GPUアクセラレーションニューラルネットワークを有効または無効にする新しい環境設定
* &lbrack;UI&amp;rbrack；改善された解像度ドロップダウン
* &lbrack;UI&rbrack;メッシュの変形、メッシュの後処理、織り込みフィルターの新しいアイコン
* &lbrack;UI&rbrack; 「共有」パネルを「書き出し」に名前変更
* &amp;lbrack；スクリプト&amp;rbrack；書き出しAPIへのレイヤー出力解像度サポートの追加
* &lbrack;Scripting&amp;rbrack；画像の読み込みAPIに切り抜き、アップスケール、ドキュメントサイズを追加
* &amp;lbrack；オンボーディング&amp;rbrack；新規チュートリアル
* &lbrack;Onboarding&rbrack; Update Welcome and What&#39;s New screens content
* &lbrack;Engine&rbrack; Substance engineをバージョン9.0.1にアップデート

**修正済み：**

* &lbrack;3D キャプチャ&rbrack; [位置合わせ]設定パラメータの[精度]オプションの名前付けを改善する
* &lbrack;Application&rbrack; 16次元の非倍数の画像を読み込むと、クラッシュする場合があります
* &lbrack;Application&rbrack;プロジェクトパネルでアセットを複製するとクラッシュする
* &lbrack;Application&rbrack;プロジェクトパネルでアセットを切り替えるとクラッシュする
* &amp;lbrack；コンテンツ&rbrack;Snowフィルターのカスタムマスクのペイントが正しく機能しない
* &amp;lbrack；公開パラメータ&amp;rbrack；公開パラメータの変更は、マテリアルの切り替え時に失われる可能性があります
* &amp;lbrack；相互運用性&amp;rbrack；書き出しパネルからマテリアルを送信すると、クラッシュする可能性があります
* &lbrack;Layers&rbrack; Content-Aware Fillは、単一の画像入力からマテリアル入力に切り替えると計算を停止します
* &amp;lbrack；マテリアルを含む環境ライトを複製するとレイヤー&amp;rbrack；がクラッシュする
* &lbrack;Layers&rbrack; Image import layerは、イメージファイルの名前が変更されると、プロパティパネルに間違ったイメージ名が表示されます。
* &lbrack;Layers&amp;rbrack；非アクティブなレイヤーに編集ボックスが表示される場合がある
* &amp;lbrack；レイヤー&amp;rbrack；画像の読み込みレイヤーで、画像の出力方法を変更しても機能しない場合がある
* &lbrack;Layers&rbrack; Creation Templateウィンドウのタイプミス(&amp;R)
* &lbrack;UI&rbrack; 3Dビューポートオンボーディングツールチップにフォーカスの問題があります
* &lbrack;UI&rbrack;ファイル名が長すぎると、イメージ名がオーバーフローする可能性があります
* &lbrack;UI&amp;rbrack；消しゴム使用時の小さなブラシツールバーレイアウトの問題
* &lbrack;UI&amp;rbrack；一部の言語では、ビューアの設定パネルで文字列が切り捨てられる
* &lbrack;UI&rbrack;ビューポートツールチップポップアップが表示されているときに[スペース]を押すと、新しいプロジェクトが作成されます

### **4.1.2カノーリ**

*（リリース：2023年6月20日）*

**修正済み：**

* &lbrack;Layers&rbrack; Substanceマテリアルやフィルターを微調整するとメモリリークが発生し、クラッシュする(&amp;L)

### **4.1.1カノーリ**

*（リリース：2023年6月6日）*

**追加済み**

* &lbrack;Engine&rbrack; Substance engineをバージョン9.0にアップデート
* &amp;lbrack；相互運用性&rbrack; 3DオブジェクトをStagerおよびPainterに送信

**修正済み：**

* &lbrack;3D キャプチャレンダラーが失敗したときの3D キャプチャクラッシュ(&rbrack; Applications)
* &lbrack;3D キャプチャ&rbrack;イメージをロードできないときのクラッシュ
* &lbrack;3D キャプチャ&rbrack;メッシュ再構築ステップに到達した際のクラッシュ
* &amp;lbrack；バウンディングボックスのサイズを変更する際の3D キャプチャ&rbrack;クラッシュ
* &lbrack;3D キャプチャ&amp;rbrack；規則に従ってマスクを読み込むと、マスクが正しく割り当てられません
* &lbrack;3D キャプチャ&rbrack;バウンディングボックスの調整中にレンダリングの不具合が発生する
* &lbrack;3D キャプチャ&rbrack; 3D キャプチャポストプロセス中のバージョンの切り替えとレンダリングオプションの切り替えに時間がかかる
* &lbrack;3D キャプチャ&rbrack; 3D キャプチャの後処理ステップ中にバージョンを切り替えると、時に破損する
* &amp;lbrack；起動時にアプリケーション&rbrack; クラッシュを起動する
* &amp;lbrack；名前を変更したマテリアルを複製する際のApplication&rbrack; クラッシュ
* 依存フォルダーなしで従来の.alchプロジェクトを開くと、&lbrack;Application&rbrack; クラッシュが発生する
* &amp;lbrack；画面のプラグを差し込んだり取り外したりしたとき、またはコンピューターがスリープ状態になったとき、またはリモートでアクセスされたときにApplication&rbrack; クラッシュが発生する
* 非永続的なアセット管理に関連するアプリケーション&rbrack; クラッシュとメモリリーク(&lbrack; Application&rbrack; Memory Leaks)
* &lbrack;Export&rbrack; テクスチャを埋め込む、または参照する3Dオブジェクトファイル形式のマテリアルフォーマットの選択を無効にする
* &amp;lbrack；書き出し&rbrack; 3Dオブジェクトの書き出し中に問題が発生した場合のクラッシュ
* .sbs/.sbsar ファイルの書き出し時に&lbrack;Export&rbrack; クラッシュが発生する
* 同じラベルを持つがファイル名が同じではないカスタムプリセットを読み込むと、&lbrack;Export&rbrack; クラッシュが発生する
* &amp;lbrack；書き出し&rbrack; sbsar ファイルbs/.sbsar ファイルに書き出せないことがある
* &amp;lbrack；書き出し&rbrack; Gltf/Glb書き出しでbase64のテクスチャがエンコードされる
* 再フォーカス時に&lbrack;Export&rbrack; Nameテキストフィールドが機能しない
* 画像をマテリアル（AI利用）レイヤーに.sbs/.sbsar ファイルとして書き出すと、&amp;lbrack；書き出し&rbrack;「タイリングを保持」が機能しない
* &lbrack;Export&rbrack; gltfを書き出してファイルを置き換える場合、置き換えられるファイルのリストが正しくありません
* &lbrack;表示されるパラメーター&rbrack;ランダムシードが、書き出された.sbs/.sbsarファイルで機能しない
* &lbrack;Layers&rbrack; Content-Aware Fillを2回目に追加するとクラッシュが発生することがある
* &amp;lbrack；画層&rbrack;レイヤースタック計算時のクラッシュ
* &lbrack;Layers&rbrack; Image to Material(AI)ディスクキャッシュが機能しない
* &amp;lbrack；レイヤー&rbrack;レイヤーを微調整するとクラッシュする可能性がある
* &lbrack;Performance&rbrack; Memory leaks
* &amp;lbrack；プロジェクトを保存するとクラッシュする(&amp;R)
* &amp;lbrack；プロジェクト&amp;rbrack；同じプロジェクトを1行に2回読み込むと、アセットが重複する
* &lbrack;UI&rbrack;アイコンのみが付いた丸みを帯びたボタンが正しくレンダリングされない

### 4.1.0カノーリ

*（リリース：2023年3月28日）*

**追加：**

* &lbrack;Content&rbrack; New Embroidery filter
* &amp;lbrack；コンテンツ&amp;rbrack；新規ペイントワープフィルター
* &lbrack;UI&rbrack;ファイルメニューの書き出しオプションを追加
* &lbrack;3D キャプチャ&amp;rbrack；戻るボタンがアラインメントステップで使用できるようになりました
* &lbrack;3D キャプチャ&amp;rbrack；画像ハンドルJPEGのEXIF方向
* &lbrack;3D キャプチャ&rbrack;スクリプティング – 新しいdataset_info.カメラプロパティ
* &lbrack;3D キャプチャ&rbrack; Linuxのサポートを追加（ドキュメントを参照）
* &lbrack;3D キャプチャ&amp;rbrack；読み込まれたイメージの読み取りアクセスを確認する
* &amp;lbrack；オンボーディング&amp;rbrack；学習 – 2つの新しいチュートリアル（刺繍とペイントワープ）
* &lbrack;Onboarding&rbrack; Updated What&#39;s New content

**修正済み：**

* &lbrack;3D キャプチャ&rbrack;バージョン変更時にカメラの位置を維持
* &lbrack;3D キャプチャ&rbrack;オブジェクトのすべてのグループを1つにマージ
* &lbrack;3D キャプチャ&amp;rbrack；生成されたメッシュの名前をオリジナルに変更
* &amp;lbrack；存在しないイメージのサムネイルを作成しようとすると、Application&rbrack; クラッシュが発生します。
* &amp;lbrack；アセット&amp;rbrack；ごみ箱アイコンがアセットパネルで何もしません
* &lbrack;Content&rbrack; マテリアルスロットでフィルターを更新すると、予期したとおりに動作しない
* &lbrack;Export&amp;rbrack；特定のフィルターを使用してアセットを書き出すと、クラッシュが発生する可能性があります
* &lbrack;Export&rbrack; SBS/SBSAR Export – イメージインポートレイヤーがイメージパラメーターよりも優先されました
* &lbrack;Export&rbrack; UE4書き出しプリセットがPNGで機能しない
* OS エクスプローラーからマテリアルとフィルターを同時に削除すると、レイヤーがクラッシュする(&lbrack; Layers&rbrack;)
* sbsar ファイルをイメージファイルと一緒にドラッグすると、&lbrack;Layers&rbrack;クラッシュが発生する。
* &lbrack;Layers&amp;rbrack；刺繍の不透明度チャンネルは完全に白にすることができます。
* &lbrack;Localization&amp;rbrack；中国語がLinuxのデフォルトで表示される場合がある
* &amp;lbrack；パフォーマンス&rbrack;アセットからレイヤーを削除する際のメモリの問題を修正
* &amp;lbrack；プロジェクト&amp;rbrack；保存時にクラッシュする可能性がある
* &lbrack;UI&rbrack;バージョンのメニューボタンの欠落したスペースを追加
* &lbrack;UI&rbrack;キャンセルボタンが正しく表示されない
* &lbrack;UI&rbrack; 3D キャプチャ後処理パラメーターのスライダーアニメーションを無効にする
* &lbrack;UI&amp;rbrack；外側をクリックしても、マテリアル作成テンプレートウィンドウが閉じない
* &lbrack;UI&amp;rbrack；外側をクリックすると、フィルタークイックアクセサーが閉じる

**既知の問題：**

* &amp;lbrack；カラーピッカー&amp;rbrack；解像度が異なる2台目のモニターでカラーを選択できない場合がある
* &lbrack;Content&rbrack; Shapeライトウィジェットが球面投影法モードで機能しません
* Stagerに送信されたディスプレイスメントを含むマテリアルのディスプレイスメントコントロールが失われます(&lbrack;Interoperability&rbrack; Material)

### 4.0.2バナナ

*（リリース：2023年3月9日）*

**追加：**

* &lbrack;3D キャプチャ&rbrack;ディスク使用量は、使用量を示します
* &lbrack;3D キャプチャ&amp;rbrack；写真の読み込みは非同期で高速です
* &lbrack;Scripting&rbrack; 3D キャプチャ機能のスクリプトを作成する新しいクラスと関数
* &lbrack;Scripting&amp;rbrack；書き出しが完了、失敗、またはキャンセルされたときにアクションを実行する新しいExportControllerクラス
* &amp;lbrack；スクリプト&amp;rbrack；引数を渡すPythonスクリプトの実行に – run-script
* レイヤーパネル上にアセットをドラッグしたときのUIフィードバック(&lbrack;UI&rbrack;)
* &lbrack;Content&rbrack; Color temperature filter is working on マテリアル
* &lbrack;Content&amp;rbrack；通常からHeightフィルターには、タイリングを保持する新しいオプションが追加されました

**修正済み：**

* &lbrack;3D キャプチャ&rbrack;データセットのアラインメントステップで画像サイズを修正
* &lbrack;3D キャプチャ&rbrack; UVラップ解除後に重複する頂点を削除する
* &lbrack;3D キャプチャ&rbrack; MacOS - 3D キャプチャが使用可能な場合の検出機能の向上
* &amp;lbrack；画像の読み込み中に3D キャプチャウィンドウを閉じると、3D キャプチャ&rbrack; クラッシュが発生する
* &amp;lbrack；新しいバージョンを生成する際の3D キャプチャ&rbrack; クラッシュ
* &amp;lbrack；ビューアに3Dオブジェクトを読み込もうとすると、3D キャプチャ&rbrack;クラッシュが発生します。
* UTF8以外の文字を含むパスを使用した場合の&lbrack;3D キャプチャ&rbrack;クラッシュ
* &lbrack;3D キャプチャ&rbrack;ヒットとヒントの誤字
* &lbrack;3D キャプチャ&rbrack; メッシュがunit cubeに合わせてスケーリングされなくなりました
* &lbrack;3D キャプチャ&rbrack;レンダリング中に3D キャプチャを閉じる際のクラッシュを防止
* &lbrack;3D キャプチャ&rbrack;マスクを削除すると画像が消える
* &amp;lbrack；アセットを2回同時に読み込む際のApplication&rbrack; クラッシュ
* &lbrack;Application&rbrack;プロジェクトを開くときに以前のバージョンのアセットがバックアップされていない場合、それらのアセットをバックアップする
* &lbrack;Application&amp;rbrack；一部のマップがベイクされていない場合にベイク済みマップを正しくキャッシュする
* &lbrack;Application&rbrack; 3Dオブジェクトを表示する際のフルスクリーンクラッシュ。
* &lbrack;Application&amp;rbrack；最後のマテリアルがプロジェクトの保存時に複製されます
* &lbrack;Application&rbrack; メッシュをキャンセルするときにクラッシュを防ぐベイクステップ中のコンピューティングの後処理
* &lbrack;Application&amp;rbrack；現在のプロジェクトを再度開いても変更が破棄されない
* &lbrack;Application&rbrack; 3Dオブジェクトのサムネール生成を停止
* &amp;lbrack；ブラシツール使用時の2D ビュー&rbrack; クラッシュ
* &lbrack;Content&rbrack; Content Aware Fill - 計算がスタックすることがある
* &lbrack;Content&rbrack; Atlas Creatorフィルターが不透明度チャンネルをダウンスケール中
* &amp;lbrack；書き出し&amp;rbrack；失敗した書き出しキューをクリアを修正
* &amp;lbrack；書き出し&rbrack; OBJの書き出しで、オブジェクトが予想の100倍小さく作成される
* &lbrack;Layers&rbrack;グレースケールチャンネルとして読み込まれたカラー画像がグレースケールと見なされるようになりました
* &lbrack;Export&rbrack; FBXファイルはサードパーティ製アプリケーションに読み込めません。
* USDファイルのシェーダー出力名が正しくない(&lbrack;Export&rbrack;)
* &lbrack;Layers&rbrack; Image name is not updated when changes its name on the OS エクスプローラー
* &lbrack;Scripting&amp;rbrack；無効なスクリプトの再読み込み時にエラーメッセージを表示
* &lbrack;UI&rbrack;ベースマテリアルボタンが使用できない場合は無効になっています
* マテリアル作成テンプレートウィンドウのファイルダイアログにアクセスするときの&lbrack;UI&rbrack; クラッシュ
* &lbrack;UI&rbrack;クイックアクセサーは、レイヤーパネルが閉じていてもアクセス可能
* &lbrack;UI&amp;rbrack；送信先アイコンの位置がずれている
* &lbrack;UI&rbrack; ブレンドアイコンをクリックすると、レイヤーアイコンが変わる

**既知の問題：**

* &amp;lbrack；カラーピッカー&amp;rbrack；解像度が異なる2台目のモニターでカラーを選択できない場合がある
* &lbrack;Content&rbrack; Shapeライトウィジェットが球面投影法モードで機能しません
* Stagerに送信されたディスプレイスメントを含むマテリアルのディスプレイスメントコントロールが失われます(&lbrack;Interoperability&rbrack; Material)

### 4.0.1バナナ

*（リリース：2023年2月7日）*

**修正済み：**

* &lbrack;3D キャプチャ&rbrack;マスクを使用すると、テクスチャ投影が壊れる可能性があります
* &lbrack;3D キャプチャ&rbrack;オブジェクトに斑点が表示される場合がある
* &lbrack;3D キャプチャ&amp;rbrack；書き出されたメッシュは本当に小さいかもしれません

**既知の問題：**

* &lbrack;3D キャプチャ&rbrack; FBXおよびOBJの書き出し結果をダウンスケール
* &lbrack;3D キャプチャ&rbrack;ハードウェアに互換性がない場合でも、MacOSで3D キャプチャを利用できます。 ドキュメントを確認します。
* メッシュ再構築が行われたときの&lbrack;3D キャプチャ&rbrack;クラッシュ。
* &amp;lbrack；レイヤー&rbrack;コンテンツに応じた塗りつぶしは、下のレイヤーを微調整するとスタックすることがある
* &amp;lbrack；カラーピッカー&amp;rbrack；解像度が異なる2台目のモニターでカラーを選択できない場合がある
* &lbrack;Content&rbrack; Shapeライトウィジェットが球面投影法モードで機能しません
* Stagerに送信されたディスプレイスメントを含むマテリアルのディスプレイスメントコントロールが失われます(&lbrack;Interoperability&rbrack; Material)

### 4.0.0バナナ

*（リリース：2023年1月31日）*

**追加：**

* &lbrack;3D キャプチャ&rbrack;イメージから3Dオブジェクトを作成
* &lbrack;3D キャプチャ&amp;rbrack；専用3D キャプチャウィザード
* &lbrack;3D キャプチャ&rbrack;データセットに黒と白のマスクを読み込むまたは生成する
* &lbrack;3D キャプチャ&rbrack;アラインメント結果 – 一致したすべてのフィーチャを点群として表示
* &lbrack;3D キャプチャ&rbrack;アラインメント結果 – 各調整された写真に関連付けられたカメラを表示して操作
* &lbrack;3D キャプチャ&rbrack;バウンディングボックスウィジェットで再構成領域を定義する
* &lbrack;3D キャプチャ&rbrack;バウンディングボックスウィジェットのすべての軸で拡大・縮小、移動、回転
* &lbrack;3D キャプチャ&amp;rbrack；再構築されたメッシュのジオメトリ精度を定義する
* &lbrack;3D キャプチャ&amp;rbrack；新しいバージョンを作成してメッシュとテクスチャを最適化する
* &lbrack;3D キャプチャ&amp;rbrack；各バージョンは、ターゲット面番号セットに自動的にデシメートされます。
* &lbrack;3D キャプチャ&amp;rbrack；後処理ステップは、テクスチャを自動的にラップ解除して再投影し、高ポリゴンメッシュから通常HeightとAO情報をベイクします
* &lbrack;3D キャプチャ&amp;rbrack；元の結果またはバージョンをSamplerプロジェクトに追加
* &lbrack;3D キャプチャ&amp;rbrack；基礎となるメッシュレイヤーのテクスチャの自動切り離し、ラップ解除、再プロジェクト、および詳細のベイクを行う新規メッシュポストプロセスレイヤー
* &lbrack;3D キャプチャ&amp;rbrack；下にあるメッシュレイヤーを拡大・縮小、変形、または移動するための新規メッシュ回転レイヤー
* &amp;lbrack；書き出し&amp;rbrack；新規書き出しウィンドウ
* &lbrack;Export&rbrack;アセットタイプ(マテリアル、環境光、メッシュ)に応じた専用の設定とUI
* &amp;lbrack；書き出し&rbrack; メッシュをUSD、USDA、USDZ、glTF、glb、obj、fbx、stlとして書き出す
* &lbrack;Export&rbrack;Substanceファイルのエクスポート時にマテリアルの種類を定義(SBSAR、SBS)
* &lbrack;UI&amp;rbrack；環境設定ポップアップの新しいタブにキャッシュ設定を移動
* &lbrack;Application&rbrack; 2Dおよび3D ビューポートのサイズ変更、入れ替え、上下へのスタックが可能
* &lbrack;Application&rbrack;スターターアセットを追加するための新しいSAMPLER_RESOURCES_PATH環境変数
* &lbrack;Scripting&amp;rbrack；起動時にプラグインとスクリプトを読み込むためのSAMPLER_PLUGIN_PATHおよびSAMPLER_SCRIPT_PATH環境変数が追加されました
* &lbrack;Scripting&rbrack; マテリアル、環境光、3dオブジェクトの書き出し機能を追加
* &amp;lbrack；スクリプト&rbrack; 識別子、デフォルト値、最小値と最大値、ラベル、および列挙値をパラメーターに追加
* &lbrack;Scripting&amp;rbrack；画像の読み込み時にカスタマイズした使用方法を入力するためのimport_emotions関数を追加しました。テクスチャの読み込み時に使用できます。

**修正済み：**

* &amp;lbrack；最近使用したプロジェクトを開いて確認ダイアログに保存するときに、アプリケーション&amp;rbrack；のクラッシュが発生する
* &lbrack;Application&rbrack; Fileダイアログで.ssaファイルを開けない
* &lbrack;Application&rbrack; FileダイアログがmacOSのバックグラウンドウィンドウに表示される
* &lbrack;Application&rbrack; 3.2プロジェクトを開くときの潜在的なクラッシュ
* &amp;lbrack；アプリケーション&rbrack;ファイルを選択すると、警告を表示する前に[ファイル]ダイアログボックスが閉じます
* &lbrack;表示されるパラメーター&rbrack;パラメトリック環境光の書き出しが機能しない
* &amp;lbrack；レイヤー&rbrack; レイヤースタックの「ここをクリックして参照」リンクが機能しない
* &amp;lbrack；レイヤー&amp;rbrack；同じレイヤー内の複数の画像のペイントが機能しない場合がある
* &amp;lbrack；レイヤー&rbrack;レイヤープロパティで画像を設定しても、画像ピッカーサムネールが更新されない
* &amp;lbrack；レイヤー&rbrack;レイヤーとして追加されたSamplerアセットの微調整が機能しない
* &amp;lbrack；プロジェクト&rbrack;プロジェクトを開くときに不要なアセットが更新される
* &lbrack;Scripting&rbrack; Windowsでプラグインフォルダーの参照が失敗することがある
* &lbrack;Pythonスクリプトで&#39;open_project()&#39;を使用すると、スクリプト&amp;rbrack；のクラッシュが発生する
* &lbrack;Scripting&rbrack; JPEGの書き出しがAPIに見つかりません
* &lbrack;Scripting&rbrack; The log panel is not read-only
* &lbrack;Scripting&rbrack; image_pickerパラメーター値が機能しない
* &lbrack;UI&rbrack;プロジェクトパネルの環境光にアセットアイコンがありません
* &lbrack;UI&amp;rbrack；環境設定ポップアップの「Designer形式に送信」ドロップダウンは空でもかまいません。
* &lbrack;UI&amp;rbrack；一部のボタンのスタイルが正しくない
* &lbrack;UI&rbrack;ラベルがボタングループウィジェットのボタンと重なる
* &lbrack;UI&rbrack; [物理サイズを設定]メニューの[ツール]にツールチップの位置が間違っています
* &lbrack;UI&amp;rbrack；言語を変更すると、ファイルメニューが正しく位置合わせされない。

**既知の問題：**

* &lbrack;3D キャプチャ&rbrack;マスクを使用すると、テクスチャ投影が壊れる可能性があります
* &lbrack;3D キャプチャ&rbrack;メッシュ変形のスケールが小さすぎると、オブジェクトに小さな斑点が現れることがあります
* &lbrack;3D キャプチャ&amp;rbrack；書き出されたメッシュは本当に小さいかもしれません。 変形のスケールをリセットして再度書き出し
* &amp;lbrack；カラーピッカー&amp;rbrack；解像度が異なる2台目のモニターでカラーを選択できない場合がある
* &lbrack;Content&rbrack; Shapeライトウィジェットが球面投影法モードで機能しません
* &lbrack;Stagerに送信されたディスプレイスメントとの相互運用性&rbrack;マテリアルは、ディスプレイスメントコントロールを失います

## バージョン3

### 3.4.1アランチーニ

*（リリース：2022年10月6日）*

**追加：**

* &lbrack;Onboarding&rbrack; New WelcomeおよびWhat&#39;s New画面
* &lbrack;Onboarding&amp;rbrack；更新されたホーム画面UI
* &amp;lbrack；オンボーディング&rbrack;ホーム画面の新しい学習コンテンツ
* &lbrack;Scripting&rbrack;メソッドが認識されない場合にログパネルにエラーを記録する
* &lbrack;Scripting&amp;rbrack；新しいssa.ヘルパーモジュールにより、ログパネルへの出力が可能
* &lbrack;Application&rbrack; Substance 3D Designerの新しいサイドバイサイドボタンウィジェットのサポート

**修正済み：**

* 見つからない画像を参照する。sbsar ファイルを書き出すときに&lbrack;Export&rbrack; クラッシュが発生する
* 破損した画像ファイルを参照してアセットを書き出すと、&lbrack;Export&rbrack; クラッシュが発生する
* &lbrack;Export&rbrack; Embroideryレイヤーを含む。sbsar ファイルを書き出すと、マテリアルがグレーになる
* &lbrack;Export&rbrack; sbsar ファイルbs/sbsar ファイルに書き出すと、完全に透明なマテリアルが生成される
* &lbrack;Export&rbrack; Normal Formatパラメータが.sbs/.sbsarファイルに正しく表示されません
* &amp;lbrack；書き出し&rbrack; .svgファイルを参照するレイヤースタックのSBS/sbsar書き出しが破損する
* &lbrack;Export&rbrack;変形したレイヤが正しく書き出されない/更新されたEnscape - Revit書き出しプリセット
* &lbrack;表示されるパラメーターを含むレイヤーを削除するときに表示されるパラメーター&rbrack; クラッシュが発生する
* &lbrack;表示されるパラメーター&rbrack; レイヤースタックで古いレイヤーを更新すると、表示されるパラメーターのリストが破損する可能性があります
* &lbrack;表示されるパラメーター&amp;rbrack；書き出してはいけないパラメータは書き出されます。
* &lbrack;表示されるパラメーター&rbrack;レイヤーを削除するときにブレンドフィルタを削除しても、そのパラメータが表示されない
* &lbrack;表示されるパラメーター&rbrack;テキストパラメーターが.sbs/.sbsarの書き出しを解除する
* &amp;lbrack；レイヤー&rbrack;レイヤースタックを別のレイヤースタックにドロップするとクラッシュが発生する。
* フィルターの読み込みに失敗したときのレイヤーのクラッシュ(&lbrack;Layers&rbrack;)
* &lbrack;Layers&rbrack; Imageフィールドのリセット時に前のイメージを再ロードできない
* &lbrack;Layers&rbrack;ツール変更の変形の取り消しまたはやり直しができない
* &lbrack;Layers&rbrack; 「すべての設定をリセット」をクリックした後にクローンスタンプレイヤーがスタックする
* &lbrack;Layers&amp;rbrack；いずれかのリセットボタンを使用すると、画像フィールドに描画できない
* &lbrack;Layers&rbrack; The Reset button not clear the drawing mask in the Image field
* &lbrack;Layers&rbrack; ImageフィールドのResetボタンは、ユーザが何かをペイントした場合は何も行いません
* &lbrack;Layers&rbrack;ブラシツール使用時にキャッシュのレンダリングが機能しない
* &amp;lbrack；レイヤー&amp;rbrack；削除されたレイヤーは、プロパティパネルに表示されます。
* &lbrack;Layers&rbrack;プロジェクトアセットの切り替え時にレイヤの計算が停止することがある
* &lbrack;Project&rbrack; Samplerがディスクからプロジェクトを開けない場合がある
* &lbrack;2D ビュー&rbrack; 2D ビューは常にデフォルトのマテリアル出力に戻ります

**既知の問題：**

* &amp;lbrack；カラーピッカー&amp;rbrack；解像度が異なる2台目のモニターでカラーを選択できない場合がある
* &lbrack;Content&rbrack; Shapeライトウィジェットが球面投影法モードで機能しません
* Stagerに送信されたディスプレイスメントを含むマテリアルのディスプレイスメントコントロールが失われます(&lbrack;Interoperability&rbrack; Material)

### 3.4.0アランチーニ

*（リリース：2022年9月6日）*

**追加：**

* &lbrack;表示されるパラメーター&amp;rbrack；新規表示されるパラーメーターパネル
* &lbrack;表示されるパラメーター&rbrack;プロパティパネルでパラメーターの表示と表示を切り替えるための「新規」ボタン
* &lbrack;表示されるパラメーター&rbrack;プロパティパネルでパラメーターを表示および表示を解除する、パラメーターに関する新しい右クリックコンテキストメニュー
* &lbrack;表示されるパラメーター&rbrack;表示されるパラメーターが表示されるパラーメーターパネルにリストされている
* &lbrack;表示されるパラメーター&rbrack;カラードットとカラーディスクが複数の場所に追加され、表示されるパラメーターを簡単に特定できます
* &amp;lbrack；公開パラメータ&rbrack;パラメータラベルは表示されるパラーメーターパネルで編集できます
* &lbrack;表示されるパラメーター&amp;rbrack；書き出し不可能なパラメータの警告を表示する
* &lbrack;表示されるパラメーター&rbrack;表示されたブレンドパラメータを含むレイヤを、非表示になった場所に移動すると、警告が表示される
* &lbrack;表示されるパラメーター&rbrack; 表示されるパラメーターは、SBSおよびSBSAR形式で書き出されます。
* &amp;lbrack；メタデータ&rbrack;カスタムメタデータテンプレートのサポート
* &amp;lbrack；メタデータ&amp;rbrack；新しいCLO物理プロパティメタデータテンプレート
* &amp;lbrack；メタデータ&rbrack;カーソルを合わせたときにアイコンを追加して、カスタムメタデータを追加または削除
* &lbrack;Python API&amp;rbrack；新しいPython API
* &lbrack;Python API&rbrack; API for Asset Authoring
* &lbrack;Python API&rbrack; API for Layers management
* &lbrack;Python API&rbrack; API for Parameters management
* &lbrack;Python API&rbrack; API for Project management
* &lbrack;Python API&rbrack;プラグインを有効または無効にできます。
* &lbrack;Python API&rbrack; Python APIドキュメントをヘルプメニューからアクセス可能
* &lbrack;Scripting&amp;rbrack；環境設定ポップアップの「新しいプラグインとスクリプト」セクション
* &lbrack;Scripting&rbrack;プラグインを作成して読み込み、独自のパネルでSamplerインターフェイスをカスタマイズする
* &lbrack;Scripting&rbrack;プラグインは、Samplerインターフェイスの一部になり、標準のSamplerパネルと同様にドッキングしたり移動したりできます。
* &lbrack;Scripting&rbrack; Samplerの右ツールバーにあるプラグイン専用のボタンバー
* &lbrack;Scripting&amp;rbrack；指定したタスクのリストを実行するスクリプトを作成およびインポートする
* &amp;lbrack；スクリプト&rbrack;スクリプトメニューからPythonスクリプトを起動
* &lbrack;Scripting&rbrack;プラグインとスクリプトは、環境設定ウィンドウから削除、並べ替え、再ロードが可能
* &lbrack;Scripting&rbrack; Added —run-scriptコマンドラインパラメータ
* &lbrack;Logs&rbrack; New Logs panel
* &lbrack;Logs&rbrack; Enable Logs panel from the Preferences window
* &amp;lbrack；ログ&rbrack;ログをクリア、コピー/ペースト、書き出しするための新しいアクションバー
* &amp;lbrack；プロパティ&rbrack;パラメータ値のリセットにカーソルを合わせる新しいボタン
* &amp;lbrack；プロパティ&rbrack;パラメータ値をリセットする新しい右クリックコンテキストメニュー
* &lbrack;Content&rbrack; Image to Image (AI Powered)がMacOSで動作するようになりました
* &lbrack;エンジン&rbrack; Substanceエンジンをv8.6.0に更新

**修正済み：**

* &lbrack;Application&rbrack;サムネールの生成中に、終了時にアプリケーションがクラッシュする場合がありました
* &lbrack;Application&rbrack;アプリケーションが終了時に「別名で保存」を使用すると、クラッシュすることがある
* &lbrack;Application&rbrack;アプリケーションが、MacOSでのシャットダウン中にハングする場合がある
* &amp;lbrack；アプリケーション&rbrack;カラーダイアログを開いたまま保存しても、変更が保存されない
* &lbrack;Export&amp;rbrack；書き出し時に使用法の命名規則が正しくない
* &amp;lbrack；レイヤー&rbrack; マテリアルをフィルターの上にドロップすると、クラッシュが発生する場合がある
* &lbrack;Layers&amp;rbrack；古いバージョンのレイヤースタックを更新すると、関連のないレイヤースタックが更新されることがある
* &amp;lbrack；メタデータ&amp;rbrack；空のフィールドが書き出される
* &lbrack;Metadata&rbrack;メタデータアイテムが1つしかない場合、UIを使用して並べ替えることができます
* &lbrack;Project&rbrack; マテリアルを複製した後にComputeが終了しない(&amp;R)
* &amp;lbrack；プロジェクト&rbrack;プロジェクトアセットが最初のプロジェクト保存後に複製されます
* &lbrack;Project&rbrack;アセットの切り替え時に不要な計算が発生する
* &amp;lbrack；レンダリング&rbrack;レイヤーを削除した後、一部のレイヤースタックが正しくレンダリングされない
* &lbrack;Security&rbrack; Fix CVE-2015-20107
* &lbrack;UI&rbrack; 2D出力がウィンドウのサイズによってぼやける可能性がある
* &lbrack;UI&rbrack;アセットプレビューは、アプリケーションがフォーカスを失ったときに上部に表示されたままになる
* &lbrack;UI&rbrack;スプラッシュスクリーンの角が丸く、不透明な背景が正方形になる

**既知の問題：**

* &amp;lbrack；カラーピッカー&amp;rbrack；解像度が異なる2台目のモニターでカラーを選択できない場合がある
* &lbrack;Content&rbrack; Shapeライトウィジェットが球面投影法モードで機能しません
* &lbrack;Stagerに送信されたディスプレイスメントとの相互運用性&rbrack;マテリアルは、ディスプレイスメントコントロールを失います

### 3.3.2ズッキーニ

*（リリース：2022年6月28日）*

**修正済み：**

* &lbrack;Application&rbrack;プロジェクトを開くときの潜在的なクラッシュを修正
* &lbrack;Export&rbrack; Samplerを再起動すると、読み込んだカスタム書き出しプリセットリストが壊れる
* &lbrack;Interoperability&rbrack; Designerから送信されたマテリアルが削除され、Designerから再送信された場合のクラッシュを修正
* &lbrack;Project&rbrack;プロジェクト内の最後のアセットである場合、最後のマテリアルまたは環境光を削除できません
* &amp;lbrack；プロジェクト&rbrack; 環境光を右クリックすると、「未保存の変更内容」アスタリスクが表示されます

**既知の問題：**

* &amp;lbrack；カラーピッカー&amp;rbrack；解像度が異なる2台目のモニターでカラーを選択できない場合がある
* &lbrack;Content&rbrack; Shapeライトウィジェットが球面投影法モードで機能しません
* &lbrack;Stagerに送信されたディスプレイスメントとの相互運用性&rbrack;マテリアルは、ディスプレイスメントコントロールを失います

### 3.3.1ズッキーニ

*（リリース：2022年6月7日）*

**追加：**

* &lbrack;Application&rbrack; Native Apple silicon (M1)サポート
* &lbrack;UI&amp;rbrack；新規ショートカット「C」キー、2D ビュー内のチャンネルを循環
* &lbrack;Tools&rbrack;ブラシツールバーでグレースケールカラー値を編集するための数値フィールド

**修正済み：**

* &lbrack;Tools&rbrack; WindowsでフラクショナルUIスケール(150%)を指定してブラシツールを使用すると、ストロークがオフセットされる
* &amp;lbrack；パフォーマンス&rbrack;メモリ消費量を改善
* 機能を有効にすると、&lbrack;物理サイズ&rbrack;物理サイズ情報が見つからない場合があります。
* &lbrack;UI&rbrack; Altキーを押すと、マウススクロールが正常に機能しない場合がある
* &lbrack;Application&rbrack; Applicationは、保存されたプロジェクトを開くときにクラッシュすることがあります
* 複数のマテリアルをドラッグ&amp;ドロップし、Application Creation Templateウィンドウでテクスチャの読み込みを使用すると、&lbrack;Application&amp;rbrack；のクラッシュが発生する
* &lbrack;Application&rbrack;カスタムフィルターを含むプロジェクトを保存する際の潜在的なクラッシュ
* &lbrack;Application&rbrack;アプリケーションの切り替え時にControlキーの状態が失われることがある
* ローカルフォルダー名を変更するときに&lbrack;Assets&rbrack; クラッシュが発生する

**既知の問題：**

* &amp;lbrack；カラーピッカー&amp;rbrack；解像度が異なる2台目のモニターでカラーを選択できない場合がある
* &lbrack;Content&rbrack; Shapeライトウィジェットが球面投影法モードで機能しません
* &lbrack;Stagerに送信されたディスプレイスメントとの相互運用性&rbrack;マテリアルは、ディスプレイスメントコントロールを失います

### 3.3.0ズッキーニ

*（リリース：2022年5月17日）*

**追加：**

* &lbrack;Content&amp;rbrack；新しいコンテンツに応じた塗りつぶしフィルター（WindowsおよびMac）
* &lbrack;Content&rbrack; Content-Aware Fillが画像、PBR マテリアル、環境光で機能しています
* &lbrack;Content&rbrack; 「タイリングを保持」パラメーターを画像からマテリアルに追加（AI搭載）
* &lbrack;Content&rbrack; 変形フィルタは、4点間のグリッドを表示できます
* &amp;lbrack；相互運用性&rbrack;マテリアルをAdobe Substance 3D Stagerに送信
* &lbrack;Tools&amp;rbrack；変形ツールまたは切り抜きツールのサイズを変更する際にCtrlキーを押して変形を中央に配置
* &amp;lbrack；ツール&amp;rbrack；変形ツールまたは切り抜きツールのサイズを変更する際にShiftキーを押して、比率を正方形にロック
* &amp;lbrack；ツール&rbrack;コピースタンプカーソルは、スタンプされる内容のプレビューを提供します
* &lbrack;Tools&rbrack;コピースタンプ使用時に消しゴムカーソルで元のコンテンツをプレビュー
* &lbrack;Tools&rbrack; Ctrl+Clickは、コピースタンプレイヤーに新しいスタンプを作成します。
* &amp;lbrack；ツール&amp;rbrack；連続するコピースタンプが1つのレイヤーにグループ化されるようになりました。
* &lbrack;Tools&rbrack; Brush Toolbar UI Revamp
* &lbrack;Tools&rbrack;セッション中はブラシツールバーの位置が固定されます
* &amp;lbrack；ツール&amp;rbrack；軸による新しいブラシ分割オプション
* &amp;lbrack；ツール&amp;rbrack；描画時に2Dビュー上でオーバーレイの表示と非表示を切り替え
* &lbrack;Tools&amp;rbrack；新しいショートカット「X」キー（ブラシと消しゴムを切り替え）
* &lbrack;Tools&amp;rbrack；新しいショートカット&quot;&lbrack;&quot; &quot;&rbrack;&quot;を使用してブラシサイズを変更
* &amp;lbrack；ツール&amp;rbrack；消しゴムを切り替えるための新しいショートカット「E」キー
* &lbrack;2Dビュー&amp;rbrack；環境光の作成時の新しい球面投影法モード
* &lbrack;2D View&rbrack;ブラシツールは、球面投影法モードでサポートされています。
* &lbrack;2D View&rbrack; Positionツールは、球面投影法モードでサポートされています。
* &lbrack;2D View&amp;rbrack；取り消し/やり直しは、球面投影法モードでサポートされています。
* &lbrack;2D View&rbrack; 球面投影法では、デフォルトの位置を設定して環境の中心を見ます。
* &lbrack;2Dビュー&amp;rbrack；新しい露出コントロール
* &lbrack;UI&rbrack;プロパティパネルの画像の微調整には、コンテンツのソース（画像またはレイヤーから）が表示されます
* &lbrack;UI&rbrack;レイヤー/マテリアル出力ドロップダウンの背景を改善
* &lbrack;UI&rbrack; 2Dビューでの解像度情報の新しい位置
* &lbrack;UI&rbrack; 3Dビューナビゲーションコントロールショートカットを含む新しいツールチップ
* &lbrack;UI&rbrack;ブラシコントロール付きの新しいツールヒント
* &lbrack;UI&rbrack; 投影のナビゲーションコントロールのショートカットを含む新しいツールチップ
* &amp;lbrack；複合フィルター&amp;rbrack；複合フィルターは、画像、PBRマテリアル、環境光に対する作業のバリエーションを処理します
* &amp;lbrack；複合フィルタ&rbrack;ツイークの順序は、複合フィルタのノードリストの順序と一致します。
* &amp;lbrack；複合フィルター&amp;rbrack；同じグループの異なるノードのツィークは、プロパティパネルの1つのグループにマージされます
* &lbrack;Application&rbrack;アセットタイプごとに専用のビューア設定を使用

**修正済み：**

* &lbrack;Application&rbrack;アプリケーションが2D ビューへの切り替え時にクラッシュすることがある
* &lbrack;Application&amp;rbrack；複数回の書き出し時にデッドロックまたはクラッシュが発生する可能性がある場合の修正
* &lbrack;Application&rbrack; Substance 3D Designerと一致するチャンネルのデフォルト値を作成する
* &lbrack;Application&rbrack;プロジェクトをロードしてもマテリアルの再計算がトリガーされない
* &lbrack;Application&rbrack;テクスチャインポートドキュメントのURLを更新
* &lbrack;Content&amp;rbrack；複合フィルターを使用している場合、再読み込み時に、更新すべきでないときに更新を要求するメッセージを表示する
* 不透明度ブレンドを使用すると、Heightマップのコンテンツの詳細が消える(&lbrack; Content&rbrack; Details)
* &lbrack;UI&rbrack;カラーダイアログで、スライダーのテキストフィールドを使用すると範囲外になる可能性があります
* &lbrack;UI&amp;rbrack；使用リストに使用できない垂直スクロールバーがあります

**既知の問題：**

* &amp;lbrack；カラーピッカー&amp;rbrack；解像度が異なる2台目のモニターでカラーを選択できない場合がある
* &lbrack;Content&rbrack; Shapeライトウィジェットが球面投影法モードで機能しません
* Stagerに送信されたディスプレイスメントを含むマテリアルのディスプレイスメントコントロールが失われます(&lbrack;Interoperability&rbrack; Material)

### 3.2.1焼き鳥

*（リリース：2022年3月8日）*

**追加：**

* &amp;lbrack；書き出し&amp;rbrack；画像ファイルのdpiメタデータの書き出し
* &lbrack;物理サイズ&amp;rbrack；物理的な寸法を編集する際に非正方形テクスチャとの比率を維持する
* &lbrack;物理サイズ&rbrack;物理サイズのメタデータは、物理サイズの変更時に即座に適用されます
* &lbrack;UI&rbrack;物理サイズが有効な場合に、あらゆる種類のHeightに影響するようにマテリアルスケールの最大スライダーを調整
* &lbrack;UI&rbrack;アセットパネルの検索フィルターの新しいツールチップ
* &lbrack;UI&rbrack;アセットパネルでボタンが無効になっている状況を説明するツールチップを使用
* &lbrack;Content&amp;rbrack；明るさコントラストフィルターの更新

**修正済み：**

* 切り抜きツールと変形ツールの&lbrack;2D ビュー&rbrack; 90度回転ボタンが正常に機能しない
* &lbrack;2D ビュー&amp;rbrack；切り抜きウィジェットが見つからないことがある
* &lbrack;Application&amp;rbrack；画像パラメーターを消去しても、基になるレイヤーが再接続されない
* &lbrack;Application&rbrack;プロジェクトの保存後の終了時のクラッシュ
* 現在のマテリアルをアセットパネルのコレクションにドラッグアンドドロップすると、&lbrack;Application&rbrack;クラッシュが発生します。
* &lbrack;Application&rbrack; ビューポートにアセットをドラッグ&amp;ドロップすると、クラッシュが発生する
* &amp;lbrack；コンテンツ&amp;rbrack；通常ブレンドにランダムシード調整があります
* &amp;lbrack；コンテンツ&rbrack;Snowフィルターの正常な出力が、新雪または雪解けのパラメーター値に応じて不正確です
* &lbrack;Content&amp;rbrack；寄木フィルタ：予期しないシームを修正
* &lbrack;Content&rbrack; Embroidery filter: remove thread in メタリック map
* &lbrack;Content&rbrack; 下限タイルフィルター： xタイルとyタイルの数を修正
* &lbrack;Content&rbrack; レンガウォールフィルター：通常とHeightを16ビットに出力
* &lbrack;Export&amp;rbrack；書き出しポップアップのデフォルトのファイル名が現在のマテリアル名ではありません
* &amp;lbrack；書き出し&amp;rbrack；書き出しプリセットを使用して物理比で書き出すと、間違った寸法が表示される
* &lbrack;Export&rbrack; MetallicがCLOエクスポートプリセットにありません
* &lbrack;Export&amp;rbrack；書き出しカスタムプリセットを置き換える場合、表示名は更新されません
* &amp;lbrack；レイヤー&amp;rbrack；最初に挿入されたレイヤーのカスタムチャンネルが検出されない
* &lbrack;Layers&rbrack; Materialは、非表示レイヤーのツイークを変更するときに再評価されます。
* &lbrack;Localization&rbrack;ツールチップが書き出しパネルでローカライズされない
* &lbrack;物理サイズ&rbrack;アセットの物理サイズを無効にしても物理スケールは削除されません
* &lbrack;物理サイズ&rbrack;Heightスケール値は、最初にスライダー境界の外側に設定することはできません
* &lbrack;物理サイズ&rbrack; 物理サイズのないイメージを読み込むと、プロジェクトを開くことができない
* &lbrack;物理サイズ&rbrack;物理サイズが見つからない場合、誤って0に設定される
* &lbrack;物理サイズ&rbrack; 物理サイズ物理スケールチェックボックスのステータスが、最初に表示されたときに更新されない
* &lbrack;UI&rbrack; ベースマテリアル &amp;Heightに対して法線にはカテゴリがありません
* &lbrack;UI&amp;rbrack；画像をペイントする際にカーソルが見えないことがあります
* &lbrack;UI&rbrack;テキストフィールドが空の場合、編集メニューの「すべてをコピー」オプションと「すべてをカット」オプションを無効にする
* &lbrack;UI&rbrack;フィルター名に間違った文字が含まれています
* &lbrack;UI&rbrack; 物理サイズロックボタンが正しいスタイルを持っていません
* &lbrack;UI&rbrack;アセットパネルの検索バーの「閉じる」ボタンで検索文字列がクリアされない

**既知の問題：**

* &amp;lbrack；カラーピッカー&amp;rbrack；解像度が異なる2台目のモニターでカラーを選択できない場合がある

### 3.2.0焼き鳥

*（リリース：2022年1月25日）*

**追加：**

* &lbrack;物理サイズ&amp;rbrack；新規物理サイズパネル
* &lbrack;物理サイズ&rbrack;マテリアル作成テンプレートウィンドウに物理サイズオプションを追加
* &lbrack;物理サイズ&rbrack; 物理サイズ計測ツールを追加
* &lbrack;物理サイズ&rbrack; 物理サイズ自動測定ツールを追加
* &lbrack;物理サイズ&rbrack; 物理サイズ診断ツールを追加
* &lbrack;物理サイズ&rbrack; 物理サイズのZ値の設定を許可する
* &lbrack;物理サイズ&rbrack; 2D ビューのズームレベルを設定するドロップダウンウィジェット
* &lbrack;物理サイズ&rbrack;ズームレベルのドロップダウンに「物理比で表示」オプションが追加されました
* &lbrack;物理サイズ&rbrack;ズームレベルドロップダウンの新しい「物理サイズに合わせる」オプション
* &lbrack;物理サイズ&rbrack; 2D ビュー内の物理サイズを表示
* &lbrack;物理サイズ&rbrack; 物理サイズを3Dビューポートで表示
* &lbrack;物理サイズ&amp;rbrack；画像の読み込みダイアログで、読み込まれた高さマップがある場合に物理サイズ深度を表示
* &lbrack;物理サイズ&rbrack;アセットのコンテキストメニューに物理サイズを表示
* &lbrack;物理サイズ&amp;rbrack；環境設定で長さの単位を設定
* &lbrack;物理サイズ&amp;rbrack；物理比に従ってテクスチャを書き出し
* &amp;lbrack；メタデータ&rbrack;ユーザーが作成したアセットにカスタムメタデータを追加する機能
* &lbrack;Export&rbrack;カスタムメタデータを.sbs(ar)ファイルにエクスポート
* &lbrack;Export&amp;rbrack；説明、カテゴリ、作成者、タグのメタデータを.sbs(ar)ファイルに書き出す
* &amp;lbrack；書き出し&rbrack; bs(ar)ファイルに書き出す
* &amp;lbrack；書き出し&rbrack; .sbsar ファイル圧縮設定を設定
* &amp;lbrack；書き出し&rbrack;アセットのサムネールを.sbs(ar)ファイルに書き出す
* &lbrack;Export&rbrack; .sbs(ar)ファイルを書き出すときにグラフの種類を設定する
* &lbrack;Application&rbrack; Realtime エンジン 2021が使用できなくなりました
* &lbrack;Application&amp;rbrack；取り消し/やり直しは、タイリング(U、V)およびHeightスケールスライダーの変更をサポートするようになりました
* &amp;lbrack；レンダリング&amp;rbrack；作成したアセットの保存時にディスクキャッシュを生成
* &amp;lbrack；アセット&rbrack; Ctrlキーを押しながらクリックして、リソースパネルで複数のアセットタイプフィルターを有効にする
* &lbrack;UI&rbrack;タイリング(U,V)スライダーをロックする機能
* &lbrack;UI&rbrack;テキストフィールドに「コピー」、「切り取り」、「貼り付け」、「すべてをコピー」、「すべてを切り取り」を含むコンテキストメニューを追加
* &lbrack;UI&amp;rbrack；長さ単位（メートル、インチ、パーセク、...） ラベルおよびテキストフィールドのサポート
* &lbrack;UI&rbrack;ユーザは、数値の表示に使用する小数点以下の桁数を設定できます
* &lbrack;UI&amp;rbrack；関連するすべての場所で単位をポップアップで使用
* &lbrack;Localization&rbrack;デフォルトの新しいアセット名がローカライズされました
* &amp;lbrack；コンテンツ&amp;rbrack；新しい布地の織りジェネレータ
* &lbrack;Content&rbrack; New Channel Switch filter
* &lbrack;Content&amp;rbrack；関連するすべてのフィルターが物理サイズを認識するようになりました
* &amp;lbrack；コンテンツ&amp;rbrack；木目仕上げの新しいアイコン
* &lbrack;Content&amp;rbrack；すべてのフィルターがAdobe標準マテリアル(ASM)チャンネルと互換性を持つようになりました
* &lbrack;Content&rbrack;フィルタに「環境」バリエーションが追加されました

**修正済み：**

* &lbrack;2D ビュー&rbrack;チャンネルを削除してもリストに残る
* &lbrack;Application&rbrack;オペレーティングシステムのファイルエクスプローラーから読み込まれたアセットを複製できません
* &lbrack;Application&amp;rbrack；終了時にクラッシュする
* &lbrack;Application&rbrack;アセットパネルで「スターターアセット」をクリックするとクラッシュすることがある
* &lbrack;Application&rbrack;マテリアルを削除するとクラッシュする
* &lbrack;Application&amp;rbrack；環境変数「SUBSTANCE_DISABLE_SPECIFIC_FEATURES」は、「0」または「0」に設定された場合もアクティブです。
* &amp;lbrack；アプリケーション&amp;rbrack；複数のマテリアルを含むプロジェクトを保存中にフリーズする
* &lbrack;Application&amp;rbrack；画像を読み込むとクラッシュする可能性があります
* &lbrack;Application&amp;rbrack；初回起動時に一部のスターターアセットが見つからない
* &amp;lbrack；書き出し&rbrack;アセットを書き出すとクラッシュすることがある
* &lbrack;Layers&amp;rbrack；レイヤーパネルが閉じているか表示されていない場合は、画像を読み込めません
* &amp;lbrack；レイヤー&amp;rbrack；言語を変更すると、現在のアセットが再計算されます
* &lbrack;Layers&amp;rbrack；読み込んだ画像の使用を変更しても、使用するフィルターバリエーションが更新されない
* &lbrack;Layers&amp;rbrack；下のレイヤーを微調整するときに、画像のマテリアルへの変換(AI)が計算されない場合がある
* &lbrack;Layers&rbrack; Image to Image (AI)が不要な場合に再計算されることがあります
* &lbrack;Layers&rbrack;ディスク上でカスタムフィルターが更新された場合、更新の提案はありません
* &lbrack;Layers&amp;rbrack；通常チャンネルが間違ったピクセル形式を持っていることがある
* &lbrack;Layers&amp;rbrack；表示されていない場合でも一部のレイヤーは計算されます
* &amp;lbrack；レイヤー&rbrack;レイヤーの表示を切り替えると、2D ビューツールが壊れる場合がある
* &amp;lbrack；レイヤー&rbrack;イメージをマテリアルに変換(AI)を使用すると、UIがフリーズする
* &amp;lbrack；レイヤー&rbrack;変形フィルターレイヤーの表示を切り替えると、2D ビューツールが機能しなくなり、クラッシュが発生する可能性があります
* &lbrack;Layers&rbrack; レイヤースタックからレイヤを削除するときに再計算が多すぎます
* &lbrack;Layers&amp;rbrack；複合フィルターに特殊な入力またはカスタム出力が含まれている場合、Samplerはそのフィルターを計算しません
* &lbrack;Performance&rbrack; Asset panel is slow to open
* &lbrack;Performance&rbrack; レイヤースタックの不必要な再計算を避ける
* &amp;lbrack；パフォーマンス&rbrack;プロジェクトアセットの読み込みに時間がかかりすぎる
* &lbrack;Performance&rbrack;ディスク上のレンダーキャッシュは使用できません
* &amp;lbrack；パフォーマンス&rbrack;レイヤー間の切り替えが遅い
* &lbrack;Performance&rbrack; マテリアルやフィルターの微調整が遅い
* &amp;lbrack；プロジェクト&amp;rbrack；終了時にプロジェクトを保存すると、クラッシュが発生する場合がある
* &amp;lbrack；レンダリング&rbrack;イメージを削除すると、すべての出力が削除される場合がある
* &amp;lbrack；レンダリング&rbrack; ビューポートに表示されているレンダリング時間が正しく表示されない
* &lbrack;UI&amp;rbrack；必要に応じて、書き出しポップアップで垂直方向にスクロールできない
* &lbrack;UI&amp;rbrack；書き出す対象がない場合、書き出しポップアップを開くことができます。
* &lbrack;UI&amp;rbrack；一部のポップアップは、コンテンツがオーバーフローした場合にスクロールされない
* &lbrack;UI&amp;rbrack；テキストフィールドをクリックしたりメニューを開いたりしても、テキストフィールドが選択されない
* &lbrack;UI&rbrack;プロパティパネルの描画モード名が正しくない場合がある
* &lbrack;UI&rbrack;ファイルメニューの「保存」オプションがグレー表示になる場合がある
* &lbrack;UI&rbrack; 2つのマテリアルの名前を変更すると、テキストフィールドが消えない
* &amp;lbrack；環境設定ポップアップのUI&amp;rbrack；誤字

**既知の問題：**

* &amp;lbrack；カラーピッカー&amp;rbrack；解像度が異なる2台目のモニターでカラーを選択できない場合がある

### 3.1.2ソコアトル

*（リリース：2021年12月14日）*

**修正済み：**

* &lbrack;Interoperability&rbrack; WindowsでBridgeからSubstance 3D Samplerで。sbsar ファイルを開くとエラーが発生する場合がある
* &amp;lbrack；レイヤー&amp;rbrack；下の唯一のレイヤーを動かすとクラッシュになります
* 言語の変更時に&lbrack;UI&rbrack;チャンネル設定ボタンが消える
* &lbrack;UI&rbrack;プロジェクトの保存後にプロパティパネルのマテリアル名が消える
* &amp;lbrack；アセット&rbrack; 「すべてのライブラリ」をクリックすると、クラッシュが発生する場合がある

**既知の問題：**

* &lbrack;Realtime Engine 2021&amp;rbrack；大量の計算でアプリケーションがクラッシュする場合がある
* &lbrack;Realtime エンジン 2021&rbrack; Realtime エンジン 2021は、AMD CPUとNvidia GPUの両方がインストールされているWindowsマシンでクラッシュします。
* &amp;lbrack；カラーピッカー&amp;rbrack；解像度が異なる2台目のモニターでカラーを選択できない場合がある

### 3.1.1クソコアトル

*（リリース：2021年11月24日）*

**追加：**

* &amp;lbrack；相互運用性&rbrack;アセット（SBSまたはSBSAR）をSubstance 3D Designerに送信
* &amp;lbrack；相互運用性&amp;rbrack；環境設定で、Substance 3D Designerとの相互運用性のデフォルトのフォーマットを設定
* &amp;lbrack；相互運用性&rbrack; Adobe Bridgeから複数のアセットを受信
* &lbrack;UI&amp;rbrack；新しいランダムシードウィジェット
* &lbrack;UI&rbrack;コンテキストメニューの更新
* &lbrack;Assets&rbrack;アセットパネルからプロパティパネルに画像をドラッグ&amp;ドロップ
* &amp;lbrack；プロジェクト&rbrack;アセット名は、特定の文字を避けるために不要な部分が削除されます。
* &lbrack;Branding&rbrack; SBSARファイルのファイルアイコンを更新
* &lbrack;エンジン&rbrack;アップデートSubstance engineバージョン8.3.0

**修正済み：**

* &amp;lbrack；コンテンツ&amp;rbrack；切り抜き – 非正方形の画像を切り抜く際に縦横比を保持する
* &lbrack;Content&rbrack; Widget - Widgetを使用する際に水平変形が反転されない
* &lbrack;Content&rbrack;Gravel – すべてのチャンネルにカスタムマスクペイントを修正
* &lbrack;Content&rbrack; 下限タイル – パターンのタイリングと繰り返しに関する問題を修正
* &lbrack;Assets&rbrack; Grey out Adobe Bridge option if not installed
* &amp;lbrack；カラーピッカー&rbrack; Escキーでカラーピッカーを閉じる
* &amp;lbrack；レンダリング&amp;rbrack；グレースケール入力を使用する場合に散乱距離スケールを修正
* &lbrack;Share&rbrack; Send toオプションは、Adobeライセンスでのみ使用できます。
* &lbrack;Project&rbrack;メモリパフォーマンスの問題を修正する

**既知の問題：**

* &amp;lbrack；リアルタイムエンジン 2021&amp;rbrack；重い計算がアプリケーションをクラッシュにする可能性があります
* &lbrack;Realtime エンジン 2021&rbrack; Realtime エンジン 2021は、AMD CPUとNvidia GPUの両方がインストールされているWindowsマシンでクラッシュします。
* &amp;lbrack；カラーピッカー&amp;rbrack；解像度が異なる2台目のモニターでカラーを選択できない場合がある

### 3.1.0ソコアトル

*（リリース：2021年9月28日）*

**追加：**

* &amp;lbrack；カラーピッカー&amp;rbrack；新規カラーピッカーUI
* &amp;lbrack；カラーピッカー&amp;rbrack；現在のカラーと以前のカラーを並べてプレビュー
* &amp;lbrack；カラーピッカー&rbrack;カラーを16進数で入力
* &amp;lbrack；カラーピッカー&rbrack;カラープレビュー付きの新しいスポイト
* &amp;lbrack；カラーピッカー&rbrack;スポイトがSamplerの外部のカラーを選択できる
* &amp;lbrack；カラーピッカー&rbrack; RGBまたはHSVカラースペースでカラーを微調整する
* &amp;lbrack；カラーピッカー&rbrack;スウォッチの保存と管理
* &amp;lbrack；相互運用性&rbrack; Image Import layerまたはImage parametersからIllustratorでイメージを編集
* &amp;lbrack；相互運用性&rbrack; Image Import layerまたはImage parametersからPhotoshopでイメージを編集
* &amp;lbrack；ウィジェット&amp;rbrack；新規切り抜きウィジェット
* &amp;lbrack；ウィジェット&rbrack; Enterキーを押して切り抜きを検証
* &amp;lbrack；ウィジェット&amp;rbrack；切り抜きウィジェットは、ウィジェットに合わせて画像サイズを読み取り、サイズ変更時に比率を維持します。
* &lbrack;UI&amp;rbrack；新しいグレースケールスライダーUI
* &lbrack;Application&amp;rbrack；環境設定に通常の形式を追加
* &lbrack;Application&amp;rbrack；画像読み込みレイヤーの標準形式は、環境設定で設定されたデフォルトの標準形式に従います
* &amp;lbrack；アプリケーション&rbrack; 2Dビューでは、環境設定で設定した標準形式に従って標準が表示されます
* &lbrack;Application&amp;rbrack；標準は、環境設定で設定された標準フォーマットでエクスポートされます
* &amp;lbrack；書き出し&rbrack; SBSおよびSBSARファイルの書き出しに通常の形式パラメーターを追加
* &lbrack;Export&rbrack; SBSおよびSBSARファイルの書き出しにシェーダ設定を追加
* &lbrack;Export&amp;rbrack；書き出したSBSグラフのデフォルト解像度を設定する
* &amp;lbrack；複合フィルター&rbrack; 7zを使用したSSAフィルターのパッケージ(&amp;R)
* &amp;lbrack；複合フィルター&amp;rbrack；複合フィルターにカテゴリメタデータを追加
* &amp;lbrack；複合フィルター&amp;rbrack；複合フィルターはサムネールを埋め込むことができます
* &amp;lbrack；複合フィルター&amp;rbrack；複合フィルター拡張機能(.ssafilter)をコンテンツの取得ダイアログに追加
* &amp;lbrack；複合フィルター&rbrack;アセットパネルの複合フィルター(.ssafilter)の読み込み
* &lbrack;Engine&rbrack; Substanceエンジンをv8.2.0にアップデート

**修正済み：**

* &lbrack;Application&amp;rbrack；接続されたローカルフォルダがハングする可能性があります
* &lbrack;Application&amp;rbrack；終了時にクラッシュする
* &lbrack;Application&rbrack; Samplerの2つのインスタンスを起動するとクラッシュする
* &lbrack;Content&rbrack; Crop filter has a random seed tweak
* &lbrack;Content&amp;rbrack；一部のSubstanceマテリアルがアップグレードされない場合があります
* &lbrack;Export&amp;rbrack；新しく追加したカスタムプリセットで書き出すとクラッシュする
* &lbrack;Export&rbrack;パッケージの推定サイズがエクスポートポップアップに表示されない
* &lbrack;Export&rbrack; SBSおよびSBSARファイルの書き出し時のメモリリークを修正
* &amp;lbrack；複合フィルター&amp;rbrack；複合フィルターの入力が重複している可能性があります
* &amp;lbrack；複合フィルター&rbrack;フィルターに満たされていない参照がある場合にクラッシュする
* &amp;lbrack；複合フィルター&amp;rbrack；複合フィルターを含むレイヤースタックを並べ替えたときのクラッシュ
* &amp;lbrack；複合フィルター&rbrack;レンダリングがハングする場合がある
* &amp;lbrack；イメージのインポート&rbrack;イメージのインポートにより複数のレンダリングがトリガーされる
* 元に戻す/やり直し時に&amp;lbrack；レイヤー&rbrack;クラッシュ
* &amp;lbrack；レイヤー&rbrack;ベースマテリアルを追加する際のクラッシュ
* &amp;lbrack；無効なイメージを環境光として使用すると、Layers&rbrack; クラッシュが発生します。
* &lbrack;Layers&amp;rbrack；複数のグラフを含むフィルターを挿入する際に重複する読み込みを修正
* &amp;lbrack；レイヤー&rbrack;レイヤーの並べ替えが常に機能しない
* &amp;lbrack；不完全なプロジェクトファイルの読み込み時にクラッシュが発生する&rbrack;
* &amp;lbrack；破損したプロジェクトを開くときのプロジェクト&rbrack; クラッシュ
* &lbrack;Project&amp;rbrack；一部のアセットがプロジェクトから消えることがあります
* &amp;lbrack；プロパティ&amp;rbrack；見つからないフィルターのプリセットを修正
* &lbrack;UI&amp;rbrack；角度パラメータを設定できません
* &lbrack;UI&rbrack;アセットパネルのメタデータ表示をフィルター
* &lbrack;UI&rbrack;カテゴリ別にグループ化するとフィルターが非表示になる
* &lbrack;UI&rbrack;アセットパネルでのスクロールの問題
* &lbrack;UI&amp;rbrack；書き出しパネルにスクロールバーが追加されました
* &lbrack;UI&amp;rbrack；画像ピッカーの一部の画像形式でサムネールが表示されない

**既知の問題：**

* &lbrack;Realtime Engine 2021&amp;rbrack；大量の計算でアプリケーションがクラッシュする場合がある
* &lbrack;Realtime エンジン 2021&rbrack; Realtime エンジン 2021は、AMD CPUとNvidia GPUの両方がインストールされているWindowsマシンでクラッシュします。
* &amp;lbrack；カラーピッカー&amp;rbrack；解像度が異なる2台目のモニターでカラーを選択できない場合がある

### 3.0.1ワッフル

*（リリース：2021年7月27日）*

**追加：**

* &lbrack;Brush&rbrack;イメージ入力がサポートしている場合は、ブラシツールのカラーを有効にする
* &amp;lbrack；ブラシ&rbrack;ブラシツールでShiftキーを押したままにすると直線が描画される
* &lbrack;Brush&rbrack; Shiftキーを押しながらブラシツールを使用すると、線のプレビューが表示される
* &amp;lbrack；ブラシ&rbrack;ブラシツールが取り消しとやり直しをサポートするようになりました
* &lbrack;2D ビュー&amp;rbrack；画像入力のデフォルトカラーがペイント時に使用される
* &lbrack;Layers&rbrack; SBSARファイルのSubstance入力デフォルト値の読み取り
* &amp;lbrack；レンダリング&rbrack;Heightを通常と結合します
* &amp;lbrack；レンダリング&rbrack;サブサーフェススキャタリングのサポート（MacOSでは使用不可）
* &lbrack;Assets&rbrack; SBSAR グラフ型を使用してアセットの種類を判別する
* &amp;lbrack；アセット&rbrack;パフォーマンスが向上した検索とアセットパネルでのアセットの検出可能性
* &lbrack;Assets&amp;rbrack；すべてのライブラリのすべてのアセットを表示する「すべてのライブラリ」エントリをアセットパネルに追加
* &amp;lbrack；アセット&rbrack;ユーザーは、アセットをカテゴリまたはタイプ別にグループ化できるようになりました
* &lbrack;Import&amp;rbrack；読み込み時に異方性、コート、光沢、Specular edge colorのテクスチャを自動検出
* &lbrack;UI&amp;rbrack；削除されたパネルのタイトルをアイコンに置き換える
* &lbrack;UI&rbrack; Textfieldsスタイルの更新
* &lbrack;UI&rbrack; 環境光テンプレート作成ウィンドウの新しい説明テキスト
* &lbrack;Application&amp;rbrack；外部アプリケーションに送信するときに、現在の解像度でアセットを書き出す
* &lbrack;Application&rbrack; マテリアルのデフォルトの解像度は2048\*2048 （macosでは1024\*1024）になりました。
* &amp;lbrack；コンテンツ&rbrack;下限タイルフィルターの新しいパターン
* &amp;lbrack；コンテンツ&rbrack;カラー置き換えフィルターの新しいデュアルカラーモード

**修正済み：**

* &lbrack;2D ビュー&rbrack;ブラシツールの最初のストロークが壊れることがある
* &lbrack;2D ビュー&rbrack;ブラシツールが表示されない場合のリソースの解放(&amp;R)
* &lbrack;2D ビュー&rbrack;変形ウィジェットで右サイズ変更カーソルを使用
* &lbrack;2D ビュー&rbrack;ウィジェットは、以前に2D ビューをパンしたことがある場合は表示されません。
* &amp;lbrack；ワークフローが壊れているプロジェクトを開くと、アプリケーション&rbrack;クラッシュが発生する
* &lbrack;Application&rbrack;アプリケーションのシャットダウンを修正して、ログが無用なエラーでフラッディングされないようにする
* &lbrack;Application&amp;rbrack；一部のオペレーティングシステムで、やり直し、削除、保存のキーボードショートカットが機能しない
* &amp;lbrack；アプリケーション&amp;rbrack；読み込みレイヤーで画像の使用状況の変更を取り消しまたはやり直しが機能しない
* &amp;lbrack；書き出し&amp;rbrack；発光色の書き出されたイメージの名前が間違っています
* SBSAR書き出し使用時、&amp;lbrack；書き出し&amp;rbrack；環境は8ビット
* &lbrack;Export&amp;rbrack；書き出した画像ファイル名の余分なスペースを削除
* &lbrack;Export&rbrack;カスタム書き出しプリセットクラッシュの置換または削除
* &lbrack;Layers&amp;rbrack；入力カウントが一致しない場合のクラッシュを回避
* &amp;lbrack；画層&rbrack;ベースマテリアル画層の挿入時のクラッシュ
* &lbrack;Layers&rbrack; Filter input count is capped to default value
* &amp;lbrack；画層&amp;rbrack；やり直しエラーにより、ブレンドの種類がHeightブレンドに変更される(&amp;R)
* &amp;lbrack；レイヤー&amp;rbrack；入力ヘッダーの上のドロップゾーンを削除
* &amp;lbrack；レイヤー&rbrack;レイヤーが入力ヘッダーの誤った場所に挿入される
* &lbrack;Layers&rbrack; 「すべての設定をリセット」ボタンで、ドロップダウンウィジェットの値がリセットされない
* &lbrack;Layers&rbrack; Undo/redo when changing an image in the Image Import layer marks the project as modified and so to save
* &lbrack;Layers&rbrack; Usage may be stopped by blend layers
* &lbrack;Project&amp;rbrack；依存フォルダーのないレガシープロジェクトを読み込むとクラッシュする
* &amp;lbrack；プロジェクト&amp;rbrack；保存後に取り消し/やり直しを使用するとクラッシュする
* &amp;lbrack；プロジェクト&rbrack;アセットを含むSbsar ファイルを開くと、マテリアル環境光が作成される
* &lbrack;Project&rbrack;マテリアル名を変更すると、サムネイルの生成が開始される場合があります
* &lbrack;Project&rbrack; マテリアル名を変更後に保存すると、そのプロジェクトが未変更としてマークされる
* &lbrack;Project&rbrack; マテリアル名を変更した後の一部の変更内容が保存されない
* &amp;lbrack；レンダリング&amp;rbrack；明るいドットが2020リアルタイムエンジンの環境に表示される
* &amp;lbrack；リアルタイムエンジン 2021を使用してサイズを変更する際のレンダリング&rbrack; クラッシュ
* &amp;lbrack；レンダリング&rbrack; Heightレベルの変更時にシャドウを再計算
* &lbrack;Assets&amp;rbrack；接続されたフォルダは、無効なファイルを追加すると新規アセットのインデックス作成を停止します。
* &amp;lbrack；アセット&rbrack;ローカルフォルダーを多くのマテリアルと接続するとクラッシュする
* &lbrack;UI&rbrack; 2D/3Dビューボタンにツールチップがありません
* &lbrack;UI&rbrack;アセットパネル内のすべてのアセットが起動時にハイライト表示される
* &lbrack;UI&rbrack;ブレッドクラムが、マテリアルの読み込み時にアセットパネルに表示されないことがある
* &lbrack;UI&amp;rbrack；言語を変更してもプロジェクトパネルに影響しない
* &lbrack;UI&rbrack;チャンネル設定パネルに従来のワークフロー情報が表示される
* &lbrack;UI&rbrack;プロパティパネルで調整が行われていないフィルターについて、「このアイテムには設定がありません」というテキストを正しく整列させる
* &lbrack;UI&amp;rbrack；要素がようこそ画面と環境設定ポップアップで正しく配置されていない
* &lbrack;UI&rbrack;パネルタイトルの幅が正しくない
* &lbrack;UI&rbrack;プロパティパネルでスクロールが壊れる場合がある
* &lbrack;UI&rbrack;スプラッシュ画面の縦横比が正しくなく、ぼやけている
* &lbrack;UI&rbrack;フルスクリーンモードがフルスクリーンではない
* &lbrack;UI&rbrack;ドッキングされていないパネルは、MacOSでアクティブになっていない場合でも、常に一番上に表示されます。
* &lbrack;UI&amp;rbrack；ようこそ画面のバナー画像を更新
* &lbrack;Content&rbrack; Tiling filterが周囲のオクルージョンチャンネルを処理しない
* &lbrack;Content&rbrack; Quilt Stitchのウェルトアセンブリシームの選択とダイアモンドパターンの問題
* &lbrack;Content&rbrack; エンボスフィルタが256 x 256 pxで動作する
* &lbrack;Content&rbrack;オフセットが0より大きい場合の下限タイルのタイリングの問題を修正

**既知の問題：**

* &lbrack;Realtime Engine 2021&amp;rbrack；重い計算、アプリケーションのクラッシュ
* &lbrack;Realtime エンジン 2021&rbrack; Realtime エンジン 2021は、AMD CPUとNvidia GPUの両方を搭載したWindowsマシンでクラッシュします。

### 3.0.0ワッフル

*（リリース：2021年6月23日）*

**追加：**

* &lbrack;Branding&rbrack; Substance AlchemistがAdobe Substance 3D Samplerになります
* &lbrack;Branding&amp;rbrack；新しいアプリケーションアイコン
* &lbrack;UI&amp;rbrack；新しいユーザーエクスペリエンスとユーザーインターフェイス
* &lbrack;UI&amp;rbrack；新規スプラッシュスクリーン
* &lbrack;UI&rbrack;パネルがインターフェイスでドッキング解除およびドッキング可能
* &lbrack;UI&amp;rbrack；同じ列に最大3つのパネルをドッキング
* &lbrack;UI&amp;rbrack；同じパネル（タブ）に最大3つのパネルをドッキング
* &lbrack;UI&rbrack;パネルのドッキングを解除して、同一または異なるスクリーンに別のウィンドウを作成
* &lbrack;UI&amp;rbrack；閉じたパネルのアイコンをクリックするとポップアップする
* &lbrack;UI&rbrack;パネルアイコンを移動して左右のバーを再配置
* &lbrack;UI&amp;rbrack；特定のフィルター（切り抜き、変形、遠近法変形、クローンスタンプ）に直接アクセスするための新しいツールバー
* &lbrack;UI&amp;rbrack；左側のバーの新しい「コンテンツを取得」ボタン
* &lbrack;UI&rbrack; 「コンテンツを取得」ボタンを使用して、アセットに直接ファイルを読み込む
* &lbrack;UI&rbrack; 「コンテンツを取得」ボタンを使用して、レイヤーに直接ファイルを読み込む
* &lbrack;UI&rbrack; 「コンテンツを取得」ボタンを使用してSubstance 3D Assets webサイトに直接アクセス
* &lbrack;UI&amp;rbrack；解像度ウィジェットにビューポートから直接アクセスできるようになりました
* &lbrack;UI&amp;rbrack；すべてのUI要素が動的にロードされるようになりました
* &lbrack;UI&rbrack;ショートカット – 「2」を使用して2Dビューの表示を切り替え
* &lbrack;UI&rbrack; ショートカット - 「3」を使用して3Dビューの表示を切り替えます。
* &amp;lbrack；ようこそ画面&rbrack; 「新規」ボタンを使用してワンクリックでプロジェクトを作成
* &amp;lbrack；ようこそ画面&amp;rbrack；新しいアートワークバナー
* &lbrack;Project&amp;rbrack；すべてのプロジェクトが一意のファイルに関連付けられるようになりました
* &amp;lbrack；プロジェクト&amp;rbrack；新規プロジェクトファイル拡張子.ssa
* &amp;lbrack；プロジェクト&rbrack;プロジェクトとして保存すると、プロジェクトの保存先を選択するように求められます
* &amp;lbrack；プロジェクト&rbrack; Samplerを閉じると、プロジェクトが保存されていない場合は保存するかどうかを確認するメッセージが表示されます
* &amp;lbrack；プロジェクト&rbrack; Samplerを閉じると、最後に保存した後に変更が加えられている場合、プロジェクトを保存するように求められます
* &lbrack;Project&rbrack;プロジェクト名がビューポートの上に表示されます
* &lbrack;Project&rbrack;プロジェクト名は、保存されていない場合、または最後の保存以降に変更が加えられている場合は、斜体で表示されます
* &lbrack;Project&rbrack; OS エクスプローラーから直接.ssaプロジェクトファイルを開く
* &lbrack;Project&rbrack; OS エクスプローラーから.sbsarを開くと、この。sbsar ファイルが使用可能な新しいプロジェクトでSamplerが起動します
* &lbrack;Project&rbrack; OS エクスプローラーから.alch （従来のSubstance Alchemistファイル）を開く
* &amp;lbrack；プロジェクトパネル&rbrack;プロジェクト内で作成されたすべてのアセットを含む新規パネル
* &amp;lbrack；プロジェクトパネル&rbrack; +アイコンを使用してアセット（マテリアルまたは環境光）を作成
* &amp;lbrack；プロジェクトパネル&rbrack;アセットを右クリックすると、コンテキストメニューが開きます
* &amp;lbrack；プロジェクトパネル&amp;rbrack；右クリックコンテキストメニューから、アセットを削除できます
* &amp;lbrack；プロジェクトパネル&amp;rbrack；右クリックコンテキストメニューから、アセットを複製できます
* &amp;lbrack；プロジェクトパネル&amp;rbrack；右クリックコンテキストメニューから、アセットの名前を変更できます
* &amp;lbrack；プロジェクトパネル&rbrack;アセットを切り替えても変更内容が失われない
* &amp;lbrack；解像度&amp;rbrack；すべてのアセットに非正方形の解像度を設定できるようになりました
* &amp;lbrack；解像度&amp;rbrack；解像度の値はプロジェクト内のアセットによって保存されます
* &lbrack;環境光&rbrack; Substance 3D Sampler内で環境光を作成
* &lbrack;環境光&rbrack; 環境光を作成するときに、ドラッグ&amp;ドロップすると環境光作成テンプレートウィンドウが表示される
* &amp;lbrack；環境&rbrack; 環境光作成テンプレートで、[環境光の読み込み]を選択して、3Dビューの環境にイメージを割り当てます
* &lbrack;環境光&rbrack; 環境光作成テンプレートで「HDR結合」を選択し、様々な露光量で複数の360度画像から環境光を作成します
* &amp;lbrack；環境光&amp;rbrack；環境光作成テンプレートで、「ビットマップとして使用」を選択してイメージを編集してから、環境光を作成します。
* &lbrack;Environment&rbrack; Image Importレイヤで環境光の使用状況を割り当て、3DビューのEnvironmentにイメージを直接割り当てます
* &amp;lbrack；環境&rbrack; 環境光チャンネルの2D ビューには、3Dビューと同じようにレンダリングを表示するための自動カラー補正があります
* &lbrack;環境光&rbrack; 環境光作成用の新しい専用コンテンツ
* &amp;lbrack；アセットパネル&rbrack;リソースとフィルターパネルが新しいアセットパネルに統合されます。
* &amp;lbrack；アセットパネル&amp;rbrack；現在、アセットパネルは、次のアセットタイプをサポートしています。マテリアル、フィルター、および画像
* &amp;lbrack；アセットパネル&amp;rbrack；すべてのスターターアセットは、「スターターアセット」セクションからアクセスできます
* &amp;lbrack；アセットパネル&rbrack;スターターアセットセクションが読み取り専用である
* &amp;lbrack；アセットパネル&amp;rbrack；新規「自分のアセット」セクション
* &amp;lbrack；アセットパネル&rbrack; 「自分のアセット」セクションは、すべてのリソースを読み込むことができる場所です
* &amp;lbrack；アセットパネル&rbrack; 「自分のアセット」内のすべてのアセットがドキュメントの特定のフォルダーに追加されます
* &amp;lbrack；アセットパネル&rbrack;アセットパネルでローカルフォルダーを接続して新しいセクションを追加
* &amp;lbrack；アセットパネル&amp;rbrack；現在のフォルダーとそのサブフォルダーが検索されます。
* &amp;lbrack；アセットパネル&rbrack;ブレッドクラムを使用してフォルダーとサブフォルダーを移動
* &amp;lbrack；アセットパネル&amp;rbrack；現在のフォルダーをマテリアル、フィルター、またはイメージでフィルターします
* &amp;lbrack；アセットパネル&amp;rbrack；複数のフィルターを組み合わせて、マテリアルと画像のみを取得
* &amp;lbrack；アセットパネル&rbrack;グリッドまたはリストを切り替えて表示を変更する
* &amp;lbrack；アセットパネル&rbrack;フィルターはアイコンで表示されます
* &amp;lbrack；アセットパネル&amp;rbrack；画像がプレビューと共に表示される
* &amp;lbrack；アセットパネル&amp;rbrack；幅を大きくすると、特定のビューでフォルダー間を移動するためのパネルのレイアウトが変更されます。
* &amp;lbrack；アセットパネル&amp;rbrack；読み取り専用でないセクションでは、アセットをドラッグしてビンアイコンにドロップし、削除します
* &amp;lbrack；アセットパネル&rbrack;アセットを右クリックすると、コンテキストメニューが開きます
* &amp;lbrack；アセットパネル&amp;rbrack；右クリックコンテキストメニューから、アセットメタデータ（名前、カテゴリ、場所）にアクセスします
* &amp;lbrack；アセットパネル&amp;rbrack；右クリックコンテキストメニューからアセットを削除します（読み取り専用ではないセクションでのみ使用可能）
* &amp;lbrack；アセットパネル&amp;rbrack；右クリックして表示されるコンテキストメニューから、Adobe Bridgeでアセットを参照します
* レイヤーの上にベースマテリアルを直接追加するための&amp;lbrack；レイヤーパネル&amp;rbrack；新規アイコン
* &amp;lbrack；レイヤーパネル&rbrack; ショートカット - Shift + Bキーを押すと、レイヤーの上にベースマテリアルが追加されます。
* &amp;lbrack；レイヤーパネル&rbrack;レイヤーにサムネールプレビュー（マテリアルサムネール、フィルターアイコンまたは画像プレビュー）が追加されました。
* &amp;lbrack；プロパティパネル&rbrack;アセット名とアセットサムネールを含むプロパティパネルのタイトルの新しいデザイン
* &amp;lbrack；プロパティパネル&rbrack;フィルターレイヤーがプリセットをサポートするようになりました
* &amp;lbrack；プロパティパネル&rbrack; Image Import Layerで、画像プレビューを右クリックしてPhotoshopで画像を編集
* &lbrack;Adobe Bridge&rbrack; Adobe Bridgeでアセットを参照すると、アセットの場所にBridgeが起動します
* &lbrack;Adobe Photoshop&rbrack; 「Adobe Photoshopで編集」を選択すると、Photoshopで画像が開いて編集できるようになります
* &lbrack;Adobe Photoshop&rbrack; Adobe Photoshopに保存するたびに、編集した画像がSamplerに再読み込みされます
* Adobe Substance 3D Designerから送信されたSubstance 3D Designer&rbrack;アセットは、アセットパネルの「自分のアセット」セクションに直接届きます。
* &lbrack;Export&rbrack;アセットをAdobe Substance 3D PainterおよびAdobe Substance 3D Stagerに直接送信
* &amp;lbrack；書き出し&rbrack; マテリアルと環境光をAdobe Substance 3D Painterに送信
* &amp;lbrack；書き出し&rbrack; 環境光をAdobe Substance 3D Stagerに送信
* &amp;lbrack；レンダリング&amp;rbrack；新規マテリアルプロパティがサポートされ、3Dでレンダリングされるようになりました。
* &amp;lbrack；レンダリング&rbrack;光沢のサポートの追加（光沢カラー、光沢の不透明度、光沢ラフネス）
* &amp;lbrack；レンダリング&rbrack;コーティングのサポートの追加（Coat color、Coat roughness、Coat normal、Coat specular level、コートIOR）
* &amp;lbrack；レンダリング&rbrack; 異方性のサポートの追加（Anisotropy levelとAnisotropy angle）
* &amp;lbrack；レンダリング&rbrack; Specular edge colorのサポートの追加
* &amp;lbrack；レンダリング&rbrack;チャンネル設定パネルでこれらの新しいプロパティを有効にする
* &amp;lbrack；レンダリング&rbrack;ベータ版での新しいリアルタイムエンジン(2021)レンダラーの導入
* &amp;lbrack；レンダリング&rbrack;ビューアの設定パネルで2つのレンダラーバージョンを切り替え
* &amp;lbrack；レンダリング&rbrack;リアルタイムエンジン(2021)レンダラーは、translucency、吸収およびスキャタリングのマテリアルプロパティをサポートします。
* &amp;lbrack；レンダリング&rbrack;リアルタイムエンジン(2021)レンダラーには、環境光からのシャドウを計算する新しい機能が導入されています
* &amp;lbrack；レンダリング&rbrack;リアルタイムエンジン(2021)レンダラーは、環境光の放射照度をリアルタイムで計算します。
* &lbrack;シェーダー設定パネル&amp;rbrack；特定のマテリアルシェーダーパラメーターを微調整するための新規シェーダー設定パネル
* &lbrack;シェーダー設定パネル&amp;rbrack；新しいパラメータ（標準スケール、Heightスケール、Heightレベル、放射強度、IOR、Coat normal強度、コートIOR）
* &lbrack;シェーダー設定パネル&rbrack;リアルタイムエンジン 2021の特定のパラメータ（表面化散乱、スキャッタリング距離、赤シフトとレイリースキャッタリング）
* &lbrack;シェーダー設定パネル&amp;rbrack；設定値はアセットごとに保存されます
* &amp;lbrack；ビューア設定パネル&amp;rbrack；デフォルト環境光のプレビューが追加されました
* &amp;lbrack；ビューア設定パネル&amp;rbrack；デフォルトメッシュのプレビューが追加されました
* &amp;lbrack；ビューア設定パネル&amp;rbrack；新しい環境不透明度パラメータ
* &lbrack;Viewer Settings Panel&amp;rbrack；新しいEnvironment blur parameter（リアルタイムエンジン 2021レンダラー専用）
* &lbrack;Localization&rbrack;ドイツ語とフランス語の新規翻訳
* &lbrack;Content&amp;rbrack；新しいデフォルトスターターマテリアル
* &lbrack;Content&amp;rbrack；新規デフォルト環境光
* &lbrack;Content&amp;rbrack；すべてのフィルターが更新、クリーンアップ、最適化されました
* &lbrack;Content&amp;rbrack；調整フィルターが複数のフィルターに分割されました
* &lbrack;Content&amp;rbrack；新しい明るさ/コントラストフィルター
* &lbrack;Content&amp;rbrack；新しい色相・彩度フィルター
* &lbrack;Content&amp;rbrack；新しい自然な彩度フィルター
* &lbrack;Content&rbrack; New Sharpen filter
* &lbrack;Content&amp;rbrack；新規標準/Height補正
* &amp;lbrack；コンテンツ&amp;rbrack；新規パネルフィルター
* &lbrack;Content&rbrack; New Smudge filter
* &lbrack;Content&rbrack; New Weaves filter
* &amp;lbrack；コンテンツ&amp;rbrack；新規ワープ変形フィルター
* &lbrack;Content&rbrack; AOフィルタへの新しいHeight
* &amp;lbrack；コンテンツ&amp;rbrack；標準フィルターへの新しいHeight
* &lbrack;Content&rbrack; Color Replace – 新しくサポートされるチャンネル（光沢、コーティング、異方性など）で置き換え
* &lbrack;Content&rbrack;カラーバリエーション – 変更するカラーを正確に選択する手動モード
* &lbrack;Content&rbrack; タイリング – カットされたシームを表示するオプション
* &lbrack;Content&rbrack; タイリング – 完全なタイリング用にカットされたシームをペイントするオプション
* &lbrack;Content&rbrack; Match – カラーとラフネスに合わせてマテリアルを追加するオプション
* &lbrack;Content&rbrack; Match – 別の画像の色に一致するように画像を処理するようになりました
* &lbrack;Content&amp;rbrack；環境光 – 新しい色温度フィルター
* &lbrack;Content&amp;rbrack；環境光 – 新しい露光量フィルター
* &lbrack;Content&amp;rbrack；環境光 – 新しい露光量プレビューフィルター
* &lbrack;Content&amp;rbrack；環境光 – 新しいNadir Patchフィルタ
* &lbrack;Content&amp;rbrack；環境光 – 新しいNadir Extractフィルタ
* &lbrack;Content&amp;rbrack；環境光 – 新しいライトフィルター（球、線、シェイプ、平面）
* &lbrack;Content&amp;rbrack；環境光 – 新しいパノラマパッチフィルター
* &lbrack;Content&amp;rbrack；環境光 – 新しい角度補正ホライズンフィルター
* &lbrack;Content&amp;rbrack；環境光 – 新しいHDR結合フィルター

**既知の問題：**

* &amp;lbrack；リアルタイムエンジン 2021&rbrack;レイアウトの変更、アプリケーションのクラッシュ
* &lbrack;Realtime Engine 2021&amp;rbrack；重い計算、アプリケーションのクラッシュ
* &amp;lbrack；パネル&rbrack; MacOS – ドッキングされていないパネルが、すべてのアプリケーションの前面に表示されます。
* &lbrack;Widgets&rbrack;変形および位置ウィジェットが消える可能性があります。 レイヤーの非表示と再表示を切り替えて表示します。
* &amp;lbrack；書き出し&rbrack; 環境光のSBSAR書き出しでは、32ビット深度の精度が失われます
* &amp;lbrack；アセットパネル&rbrack;アセットは、フォルダーを開くときにハイライト表示できます
* &amp;lbrack；プロパティパネル&rbrack;パラメーターをリセットしてもコンボボックスUIがリセットされない
* &lbrack;Localization&amp;rbrack；言語を変更しても、再作成されるまでプロジェクトパネルに影響しない

## バージョン2

### 2.3.2(2020.3.2)バーミセリ

*（リリース：2021年2月23日）*

**追加：**

* &amp;lbrack；ローカライズ&amp;rbrack；日本語サポート

**修正済み：**

* &amp;lbrack；レイヤー&amp;rbrack；刺繍フィルターでマテリアルを微調整すると、刺繍の画像が失われる

**既知の問題：**

* 高解像度の画像でのImage to Material（AI搭載）の使用は遅くなる可能性があります
* 高解像度で、コンテンツに応じた塗りつぶしフィルターの処理が遅い
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます
* まったく同じマテリアルレイヤースタックを2回保存できない

### 2.3.1(2020.3.1)バーミセリ

*（リリース：2020年12月17日）*

**追加：**

* &lbrack;エンジン&rbrack; Substance engineの更新
* &amp;lbrack；特定の機能を無効にするアプリケーション&amp;rbrack；環境変数
* &lbrack;Content&rbrack; Replace color - New Advanced segmentation option
* &lbrack;Content&rbrack; 下限タイル – 使用可能な新しいパターンとオプション
* &lbrack;Content&rbrack; Embroidery – フィルターの完全な改良
* &lbrack;Content&amp;rbrack；補正 – 新しいメタリックパラメータ+不透明度セーフ変形補正

**修正済み：**

* &amp;lbrack；画層&amp;rbrack；同じカスタムフィルタを2回読み込むことはできません
* &lbrack;Layers&rbrack;ブラシツールでイメージ入力を使用できない
* &amp;lbrack；書き出し&rbrack; .jpgを.jpegの代わりに書き出す
* &lbrack;UI&amp;rbrack；ようこそ画面の画像クレジットを更新
* &lbrack;UI&rbrack;メニューの非表示セパレータを修正
* &lbrack;UI&rbrack;ラジオボタンが切り詰められると、ツールチップが表示されます
* &lbrack;UI&rbrack; Typo: スターターマテリアル
* &lbrack;Application&rbrack;アセット名のUTF-8文字が機能しない
* &lbrack;Localization&amp;rbrack；中国語ロケールのイタリック体フォントスタイルを無効にする
* &lbrack;Localization&amp;rbrack；ローカライズされた文字列を2行に分割
* &lbrack;Localization&rbrack;フォルダ名を調整し、長すぎる場合は省略記号に置き換える
* &amp;lbrack；ローカライズ&amp;rbrack；桁区切り記号を使用して数値を書式設定(&amp;R)
* &lbrack;Localization&rbrack; Localize date and time display
* &lbrack;Localization&rbrack; Localize color picker on Windows
* &amp;lbrack；コンテンツ&rbrack;変形 – セーフ変換をアクティブにすると、法線が45°ごとに正しく回転します。
* &lbrack;Content&rbrack; Surface リリーフ - perlinフラクタルノイズのタイリングの問題を修正（高度なノイズ）
* &lbrack;Content&rbrack; Brickwall Pattern - 16ビットのHeight入力
* &lbrack;Content&rbrack; マテリアルアイコンレンダリング – Specularのリフレクションの問題
* &lbrack;Content&rbrack; Color Variation – カラー入力と結果間でカラーシフトがありません
* &amp;lbrack；コンテンツ&rbrack;カラーバリエーション – パフォーマンスの更新

**既知の問題：**

* 高解像度の画像での画像からマテリアルへの変換（AI搭載）の使用は遅くなることがあります
* 高解像度で、コンテンツに応じた塗りつぶしフィルターの処理が遅い
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます
* まったく同じレイヤースタックを2倍保存できない

### 2.3.0(2020.3.0)バーミセリ

*（リリース：2020年10月26日）*

**追加：**

* &amp;lbrack；イメージをマテリアルに&rbrack; NVIDIA RTX 3000シリーズのサポート
* &amp;lbrack；イメージをマテリアルに&amp;rbrack；ジオメトリの詳細を制御する新しいパラメータ
* &amp;lbrack；イメージをマテリアルに&rbrack;ラフネスを制御する新しいパラメータ
* &amp;lbrack；イメージをマテリアルに&amp;rbrack；発光の強さを制御する新しいパラメータ
* &amp;lbrack；サムネール&rbrack; Substance DesignerのPBRレンダラーに基づく新しいサムネールジェネレータ
* &amp;lbrack；サムネール&rbrack;サムネールを埋め込むようにベースマテリアルとアトラスを更新する
* &lbrack;Thumbnails&rbrack; .sbsar ファイルが存在する場合は、そこからサムネールを取得する
* &amp;lbrack；サムネール&amp;rbrack；環境設定でサムネールの画質を変更
* &lbrack;エンジン&rbrack; Substance engineバージョン8に更新
* &amp;lbrack；ローカリゼーション&amp;rbrack；中国語ローカリゼーション
* &lbrack;UI&amp;rbrack；試験的スポットカラーピッカー
* &amp;lbrack；コンテンツ&amp;rbrack；新規環境マップ - Studio 06
* &lbrack;Content&rbrack; Add Atlas Generator filter
* &lbrack;Content&rbrack; Add Atlas Splitterフィルタ
* &lbrack;Content&rbrack; Add Discarded Gums filter
* &amp;lbrack；コンテンツ&amp;rbrack；指紋フィルターを追加
* &lbrack;Content&rbrack; Add Scratchesフィルタ
* &lbrack;Content&rbrack; Add Surfaceリリーフフィルタ（replace Heightモジュレーションフィルタ）
* &amp;lbrack；コンテンツ&rbrack;ワープフィルターを追加
* &lbrack;Content&rbrack; Add Invert filter
* &lbrack;Content&rbrack; Add Colorize filter
* &lbrack;Content&rbrack; Add Replace Color Fitler
* &lbrack;Content&rbrack;変形 – 特定のチャンネルでトランスフォームをディアクティベートする機能を追加します。
* &lbrack;Content&rbrack; Rotation – セーフ変形がアクティブな場合に変形を追加
* &lbrack;Content&rbrack; Color Variation – セグメント化オプションを追加して、色の分散方法を選択します

**修正済み：**

* &lbrack;Layers&amp;rbrack；複数の取り消し/やり直し操作を行うときに、UIが正しく更新される
* &amp;lbrack；レイヤー&amp;rbrack；複数の取り消し/やり直し操作を行うときにクラッシュを防止
* Image to Device (AI Powered)を使用しているときにlog: invalid device ordinalが発生した場合、&amp;lbrack；レイヤー&rbrack; クラッシュが発生します。
* &amp;lbrack；フィルター&rbrack; NVidia固有の機能のNVIDIAグラフィックカード検出を改善
* &amp;lbrack；アプリケーションを閉じるときのアプリケーション&rbrack; クラッシュ
* &lbrack;Application&rbrack; MacOSでのVRAMの金額検出の修正
* &lbrack;Export&amp;rbrack；一部の書き出しプリセットが見つからない
* &lbrack;Content&amp;rbrack；油彩エフェクト – 高ディスプレイスメント振幅でHeight範囲を修正
* &lbrack;Content&rbrack; Make It Tile Advanced - No washed out basecolor at export
* &lbrack;Content&rbrack; Make It Tile Advanced - AOが強すぎる場合、ベースカラーの白いマスク
* &lbrack;Content&amp;rbrack；調整 – 画像で機能するようになりました(scan1, ...)

**既知の問題：**

* 高解像度の画像でのImage to Material（AI搭載）の使用は遅くなる可能性があります
* 高解像度で、コンテンツに応じた塗りつぶしフィルターの処理が遅い
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます
* まったく同じマテリアルレイヤースタックを2回保存できない

### 2.2.1(2020.2.1)うどん

*（リリース：2020年7月21日）*

**追加：**

* &lbrack;Layers&rbrack; In App Error message when Image to Material (AI-Powered)がメモリ不足です

**修正済み：**

* &lbrack;Layers&rbrack; Image to Material （AI搭載）が、Specular/光沢ワークフローでは機能しません
* &lbrack;Layers&amp;rbrack；画像からマテリアルへ（AIを使用）を使用中にビデオメモリが不足するとクラッシュする
* &lbrack;Layers&rbrack; Disk cache is not used for display when opening a スタック
* &amp;lbrack；レイヤー&rbrack; Nvidia RTX 8000の検出
* &lbrack;Layers&rbrack;スプラッタ入力の外側にレイヤを移動できないことがあります
* &lbrack;Layers&rbrack; Disk cache is not used when inserting a スタックをスタックに挿入するとき
* &lbrack;Layers&amp;rbrack；一部のチャンネルの使用は計算されますが、使用されません。
* &lbrack;Layers&amp;rbrack；画像を読み込むと空白の出力が作成されることがある
* &lbrack;2D ビュー&amp;rbrack；描画モードがアクティブなブロックを含む別のレイヤーに切り替え、パンとズーム
* &lbrack;Content&rbrack;Snow- 法線マップの8ビット問題
* &amp;lbrack；コンテンツ&amp;rbrack；舗装パターン – 法線マップ上の8ビット問題
* &lbrack;Content&rbrack; Equalizer - 法線マップの8ビットの問題
* &lbrack;Content&rbrack; Gravel Generator - 法線マップの8ビット問題
* &lbrack;Content&rbrack; 下限タイル – 不透明度とSpecular levelを処理
* &lbrack;Content&rbrack; Blender cycles eeeve export preset - 法線マップを反転
* &amp;lbrack；コンテンツ&amp;rbrack；画像からマテリアルへの変換（AIを利用）で発生する巨大な画像の問題を修正
* &lbrack;Application&rbrack;データベースのエラー時に「バックアップして再起動」を選択するとクラッシュが発生する
* 同じアセットをすばやくクリックしたときのクラッシュ(&lbrack;Application&rbrack;)
* &lbrack;Application&amp;rbrack；終了時の希少クラッシュ
* &amp;lbrack；ようこそ画面にファイルをドロップするときにクラッシュが発生する&rbrack;
* 破損した環境ファイルが読み込まれたときに発生するアプリケーションのクラッシュ(&lbrack;Application&rbrack;)
* &lbrack;Application&rbrack;レンダリングされたアセットを迅速に切り替えるときに、まれに発生するクラッシュ
* &lbrack;Application&rbrack;アセットの計算中に終了するとフリーズする
* &lbrack;Application&rbrack; Macosの起動時に発生する稀なクラッシュ
* &amp;lbrack；アプリケーション&amp;rbrack；起動後すぐにアプリケーションを閉じるとデッドロックが発生する
* &amp;lbrack；レンダリング&rbrack; 3Dビューがちらつく
* &lbrack;UI&rbrack;カラーピッカーとランダムシードウィジェットが、残りの微調整と一致しない
* &amp;lbrack；レンダリング&amp;rbrack；間違った計算時間が表示される
* &lbrack;Export&amp;rbrack；一部の書き出しプリセットが見つからない

**既知の問題：**

* 高解像度の画像でのImage to Material（AI搭載）の使用は遅くなる可能性があります
* 古いNVIDIAドライバー（400.x未満）でDelighterがクラッシュする
* 高解像度で、コンテンツに応じた塗りつぶしフィルターの処理が遅い
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます
* まったく同じマテリアルレイヤースタックを2回保存できない

### 2.2.0(2020.2.0)うどん

*（リリース：2020年6月15日）*

**追加：**

* &lbrack;Create&rbrack; WindowsおよびLinuxで利用可能なNew Image to Image (AI powered)フィルタ
* &amp;lbrack；作成&rbrack;ビットマップをマテリアルに名前変更してイメージをマテリアル(B2M)に変更
* &lbrack;Image Import&rbrack; New マテリアル作成テンプレートポップアップ
* &lbrack;Image Import&rbrack; New &quot;ベースマテリアルを追加&quot;オプション
* &amp;lbrack；画像の読み込み&amp;rbrack；追加の画像をマテリアル作成テンプレートにドラッグ&amp;ドロップ可能
* &lbrack;Image Import&rbrack; Be able to remove images in the Image Creation Template
* &lbrack;Image Import&rbrack;ファイル名に基づいて読み込まれたビットマップにチャンネルを自動的に割り当てる
* &amp;lbrack；イメージの読み込み&amp;rbrack；法線マップを反転できる
* &lbrack;2D View&rbrack;ペイントモードの導入
* &lbrack;2D ビュー&amp;rbrack；絵画タイル
* &lbrack;2D ビュー&rbrack;ブラシカラーのグレースケール値を設定する
* &lbrack;2D ビュー&rbrack;ペイント中にパンとズーム
* &lbrack;2D ビュー&rbrack;ブラシのグレースケール値を反転するX ショートカット
* &lbrack;2D View&rbrack; &amp;lbrack；および&rbrack;ショートカットによるブラシサイズの変更
* &lbrack;2D ビュー&rbrack; Ctrl （またはCmd） +マウスホイールでブラシサイズを変更
* &lbrack;2D ビュー&rbrack;クローンパッチを使用する際に、ソース位置を変更できるようになりました。
* &lbrack;Layers&rbrack; Shiftキーを押しながらアトラスを自動散乱にドラッグ&amp;ドロップ
* &lbrack;Layers&rbrack; Altキーを押しながらドラッグ&amp;ドロップすると、マテリアルがデカールとして挿入されます
* &amp;lbrack；レイヤー&rbrack;Substance Designerからマトリックスの変形を簡単に表示
* &lbrack;Layers&amp;rbrack；空でないスタックにテクスチャをドロップすると、適切なチャンネルに自動的に割り当てられます
* &amp;lbrack；画層&amp;rbrack；新しいタイプの画層：合成フィルタ
* &amp;lbrack；パラメータ&rbrack;Substance文字列入力をサポート
* &lbrack;UI&rbrack;ポップアップとメニューにドロップシャドウを追加
* &lbrack;UI&amp;rbrack；右クリックオプション（クリア、コピー、ペースト）を使用した新しいカラーウィジェット
* &lbrack;UI&rbrack;ペイントツールオプションを使用した新規画像ウィジェット
* &lbrack;UI&amp;rbrack；画像ウィジェット内の読み込まれた画像にペイントを合わせることができます。
* &amp;lbrack；レンダリング&amp;rbrack；新規デフォルトカメラ位置
* &lbrack;Export&rbrack; SubstanceファイルがSubstance Designer 2020.1.2(10.1.2)にエクスポートされる
* &amp;lbrack；パフォーマンス&rbrack;アプリケーション起動時間の改善
* &lbrack;Performance&amp;rbrack；非同期タスク処理の改善
* &amp;lbrack；パフォーマンス&rbrack;レイヤーの追加、削除、移動時にレイヤースタックのパフォーマンスを向上
* &amp;lbrack；パフォーマンス&rbrack;イメージからマテリアルへ（AI搭載）は、RTX GPUでより高速に実行されます。
* &lbrack;Content&amp;rbrack；新規メッシュ：女性Tシャツ、男性Tシャツ、靴
* &lbrack;Content&amp;rbrack；新規ブレンドモード – チャンネルごとのブレンド
* &lbrack;Content&amp;rbrack；不透明度ブレンドHeight補正、2つの新しいパラメーター（Height位置とHeightスケール）
* &lbrack;Content&rbrack; ブレンドモードでHeight調整を追加
* &lbrack;Content&rbrack; Use information option in the Custom Mask ブレンド
* &lbrack;Content&amp;rbrack；新しい遠近法補正ツール
* &lbrack;Content&rbrack; Pattern Generator – パターンを反転するパラメータを追加します
* &lbrack;Content&rbrack; Pattern Generator – 新しいパラメータを追加します。 マテリアルの詳細のオーバーライド
* &lbrack;Content&rbrack; New Decal filter
* &lbrack;Content&rbrack; New Moss filter
* &lbrack;Content&amp;rbrack；新しい亀裂フィルタ
* &lbrack;Content&amp;rbrack；新しいPBR 検証フィルタ
* &lbrack;Content&amp;rbrack；新しい下限タイルフィルター
* &lbrack;Content&rbrack; New Quilt Stick filter
* &lbrack;Content&rbrack; Atlas Scatter – カスタムマスク入力を追加してペイントオプションを有効にする
* &lbrack;Content&rbrack; Dirt – カスタムマスク入力を追加してペイントオプションを有効にする
* &lbrack;Content&rbrack; CLO export preset
* &lbrack;Content&rbrack; VStitcher書き出しプリセット
* &lbrack;Content&rbrack; Unity HDRPプリセットがdetailMapをエクスポートする

**修正済み：**

* &amp;lbrack；レイヤー&amp;rbrack；読み込んだ画像の読み込み回数が多すぎます
* &amp;lbrack；レイヤー&rbrack;スタックの一番下にコピーパッチを作成するとクラッシュする
* &amp;lbrack；レイヤー&rbrack;スタックの一番下にマテリアルを追加すると、そのマテリアルが不安定になる
* &amp;lbrack；レイヤー&amp;rbrack；画像の読み込み後にフィルターが正しく動作しない
* カスタムフィルターを使用してプロジェクト間でワークフローを切り替える場合、&lbrack;Layers&rbrack; workflow_typeの値が更新されない
* &lbrack;Layers&rbrack;レイヤが選択されていない場合は「レイヤを削除」ボタンを無効にする
* &amp;lbrack；レイヤー&rbrack;クローンパッチを含むアセットを読み込むとクラッシュする
* &lbrack;Layers&rbrack; Normal to HeightフィルターがMacOsでクラッシュする
* &lbrack;Application&amp;rbrack；前後の環境マップをロードするとクラッシュする
* &amp;lbrack；アプリケーション&amp;rbrack；一部のグラフィックタブレットドライバーがインストールされている場合のパフォーマンスの問題
* &lbrack;Application&rbrack; EXR 32ビットファイルの読み込みが黒になる
* &lbrack;Application&rbrack;アセットのロードおよびアンロード時にクラッシュする
* &amp;lbrack；アプリケーション&amp;rbrack；検索から作成に切り替えるとクラッシュする
* &amp;lbrack；マテリアルを保存する際のターゲットコレクションが現在のプロジェクトのものでない場合(&rbrack;)
* &lbrack;Application&rbrack;バックアップを修正して再起動
* &amp;lbrack；画像の読み込み&rbrack; グレースケールイメージを正しく読み込む
* &lbrack;Content&amp;rbrack；新しいマトリックス処理用の新しいフィルタ
* &lbrack;Content&amp;rbrack；読み込んだカスタムフィルターがクイックアクセスバーに表示される
* &lbrack;Content&rbrack; Make it tile advanced filterでカラーシフトを修正
* &amp;lbrack；パフォーマンス&rbrack;カラーダイアログを開く動作が遅いため、現在のレイヤーを再計算します
* &lbrack;UI&rbrack;キーボードショートカットが機能しない場合がある
* &lbrack;2D ビュー&rbrack;コンテンツに応じた塗りつぶしを使用するには、最初のクリックが不要です
* &lbrack;Resources&rbrack;フォルダを削除した後も、ローカルディスク内のフォルダは更新を監視されます。
* &lbrack;Resources&rbrack;ファイルシステムからリンクされたフォルダを削除しても削除されない
* &lbrack;Export&rbrack;カスタム書き出しプリセットのカスタム使用が書き出されない
* &lbrack;Export&rbrack;パスに特殊文字を含む。sbsar ファイルの書き出しに失敗する

**既知の問題：**

* イメージのマテリアルへの再計算を繰り返し行うと（AI搭載）、クラッシュがトリガーされることがある（メモリ不足）
* Delighterを繰り返し再計算すると、（メモリ不足の）クラッシュが発生する可能性があります
* 高解像度の画像での画像からマテリアルへの変換（AI搭載）の使用は遅くなることがあります
* VRAMが少ないGPUで画像からマテリアル（AI搭載）を使用すると、（メモリ不足の）クラッシュがトリガーされることがあります。
* PBR Specular/光沢度では、画像からマテリアル（AI搭載）は使用できません
* 古いNVIDIAドライバー（400.x未満）のクラッシュを喜ばせる
* 高解像度で、コンテンツに応じた塗りつぶしフィルターの処理が遅い
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます
* まったく同じレイヤースタックを2倍保存できない

### 2.1.1 (2020.1.1)ティラミス

*（リリース：2020年4月1日）*

**追加：**

* &amp;lbrack；プロジェクト&rbrack;メタデータの書き出しと読み込み
* &lbrack;Application&rbrack; Ctrl+Sでプリセットをエクスプローラーに保存
* &lbrack;Performance&amp;rbrack；最大2Kの解像度の保存マテリアルを再計算する代わりにレンダーキャッシュを使用

**修正済み：**

* &lbrack;UI&rbrack; ビューポートの計算中の固定インジケータ
* &lbrack;UI&rbrack;スライダーへの負の値の入力は修正されました
* &lbrack;UI&rbrack;コンボボックス：キーボード矢印とスクロールバーが機能するようになりました
* &lbrack;UI&rbrack; 2D ビューで「マテリアル出力」と「レイヤー入力」を切り替えるときに、選択したチャンネルを維持
* &amp;lbrack；レイヤー&rbrack;ベースマテリアルにカスタムチャンネルを追加する際のクラッシュを修正
* &amp;lbrack；レイヤを操作するときのレイヤのクラッシュ(&rbrack;)
* &lbrack;Layers&rbrack;カスタムチャンネルが保存されたマテリアルと一緒に表示されない
* &lbrack;Application&rbrack;アセットの読み込み時の稀なクラッシュを修正
* &lbrack;Application&amp;rbrack；終了時のクラッシュ
* &lbrack;Application&rbrack;コンボボックスは、プリセットの切り替え時に正しい値を表示するようになりました
* &lbrack;Export&rbrack; Enscapeプリセットの名前をEnscape Revitに変更
* &lbrack;Export&amp;rbrack；削除後の書き出しプリセットの読み込み機能
* &amp;lbrack；書き出し時の書き出し&rbrack; クラッシュ
* &amp;lbrack；レンダリング&rbrack;base colorが16 bit half floatフォーマットの場合のレンダリングを修正
* &lbrack;Project&amp;rbrack；破損したパッケージを読み込むときにクラッシュしない
* &lbrack;Project&rbrack; Createが開かれていない場合の2019.1.4から2.x.xへの移行を処理する
* &lbrack;Project&amp;rbrack；同じプロジェクトを2回読み込んだときのクラッシュを修正
* &lbrack;Project&rbrack;プロジェクトの読み込み時のクラッシュの修正
* &amp;lbrack；リソース&amp;rbrack；以前のバージョンで読み込まれたカスタムフィルターが動作する
* &lbrack;Resources&amp;rbrack；同じ名前のマテリアルが互いに消去されなくなりました
* &lbrack;Resources&rbrack;ローカルフォルダーをリンクするときのクラッシュ
* &lbrack;Resources&rbrack; スターターマテリアルのユーザ作成フォルダが再起動後に削除されなくなりました
* &lbrack;Inspire&amp;rbrack；未保存のマテリアルを使用している場合は、マテリアルやコレクションのドロップエリアを修正して警告メッセージを追加

**既知の問題：**

* 高解像度で、コンテンツに応じた塗りつぶしフィルターの処理が遅い
* 1つのマテリアルに複数の区切り記号を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）のクラッシュを喜ばせる
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます

### 2.1.0(2020.1.0)ティラミス

*（リリース：2020年3月12日）*

**追加：**

* &lbrack;Export&rbrack;レンダラとゲームエンジン用にテクスチャをパックするプリセットの選択をエクスポートする
* &amp;lbrack；書き出し&rbrack;プリセットをUnreal エンジン 4に書き出し
* &lbrack;Export&rbrack;プリセットをUnity Standardにエクスポート
* &lbrack;Export&rbrack;プリセットをUnity HDRPにエクスポート
* &amp;lbrack；書き出し&rbrack;プリセットをブレンダーサイクル/イベントに書き出し
* &lbrack;Export&rbrack;プリセットをArnold 5に書き出し
* &amp;lbrack；書き出し&rbrack;プリセットをコロナレンダラーに書き出し
* &lbrack;Export&rbrack;プリセットをEnscapeに書き出し
* &amp;lbrack；書き出し&rbrack;プリセットをKeyshot 9に書き出し
* &lbrack;Export&rbrack;プリセットをRedshiftに書き出し
* &amp;lbrack；書き出し&rbrack;プリセットを次のVrayに書き出し
* &lbrack;Export&rbrack;プリセットをLens Studioに書き出し
* &amp;lbrack；書き出し&rbrack;プリセットをSpark AR Studioに書き出し
* &amp;lbrack；書き出し&rbrack; PBR メタリックラフネスからプリセットをPBR Specular光沢度に書き出し
* &amp;lbrack；書き出し&amp;rbrack；新しい書き出しUI
* &amp;lbrack；書き出し&rbrack;エクスポート設定を保存
* &lbrack;Export&rbrack;カスタム書き出しプリセットの読み込みと管理
* &lbrack;Export&rbrack;カスタム書き出しプリセットの削除と置換
* &amp;lbrack；書き出し&rbrack;カスタム書き出しプリセット名を変更
* &lbrack;Export&rbrack;デフォルトのエクスポート解像度を現在の解像度に設定します
* &lbrack;Export&amp;rbrack；書き出し場所にサブフォルダーを作成する選択を追加
* &lbrack;Export&amp;rbrack；既存のファイルを置き換える前に警告メッセージを表示
* &lbrack;Application&amp;rbrack；新しいバージョン番号付けスキーム
* &lbrack;Application&amp;rbrack；起動時にCreateを開き、ラボの順序を変更
* &amp;lbrack；ようこそ画面&amp;rbrack；新しいようこそバナー
* &amp;lbrack；プロジェクト&amp;rbrack；起動時に最後のプロジェクトを開く
* &lbrack;UI&amp;rbrack；新規コンボボックススタイル
* &lbrack;2D ビュー&rbrack; 2dビューでフォーカスするF ショートカット
* &lbrack;Filters&rbrack; グラフでalchemist::parameterVisibilityタグをサポートするようになりました
* &lbrack;Filters&rbrack;ワークフローに基づいてパラメーターの表示を管理するためのグローバルな微調整を行う
* &lbrack;Resources&amp;rbrack；設定ファイルを使用してリソースとリンクされたフォルダを設定するための新しいコマンドラインオプション
* &amp;lbrack；バージョンチェッカー&rbrack;バージョンチェックの設定
* &lbrack;Content&amp;rbrack；新しいスターターマテリアル
* &lbrack;Content&rbrack;ビットマップをマテリアルに変換 – メタリックのチャンネル（均一、カスタム画像の読み込み、カラー選択）を定義できるようになります。
* &lbrack;Content&rbrack;Adjustment - PBR Specular/光沢ワークフローのサポートを追加
* &lbrack;Content&rbrack; Atlas Scatter – 新しいパラメータ

**修正済み：**

* &amp;lbrack；同じプロジェクトを2回読み込んだときのプロジェクト&rbrack; クラッシュ
* &amp;lbrack；プロジェクト&rbrack;プロジェクトを何度も読み込んだり開いたりするときのクラッシュを修正
* &amp;lbrack；名前のないマテリアルを読み込むときのApplication&rbrack; クラッシュ
* &lbrack;Application&amp;rbrack；見つからないファイルを再読み込みするときに認識する(&amp;R)
* &amp;lbrack；アプリケーション&rbrack;シャットダウン時にランダムにクラッシュする問題を修正
* &lbrack;Application&rbrack; Createでマテリアルをアンロードする際の稀なクラッシュを修正
* &amp;lbrack；アプリケーション&rbrack; UIコントロール使用時のランダムなクラッシュを修正
* &lbrack;Application&rbrack; Windows 10でのログファイルのデスクトップへの書き出しを修正
* &lbrack;UI&amp;rbrack；書き出しパネルを「作成」で開くと、間違ったサイズになる
* &lbrack;UI&rbrack;ワンクリックでプロジェクトを開く
* &lbrack;UI&amp;rbrack；最小および最大スライダー値を正しく設定
* &lbrack;UI&rbrack; IDの代わりにチャンネル使用状況のラベルを表示
* &lbrack;UI&rbrack;マテリアルをクリックすると、常にツイークパネルが開いたり閉じたりします
* &lbrack;UI&amp;rbrack；非表示レイヤーの色を修正
* &lbrack;UI&amp;rbrack；ようこそ画面のボタンの改善
* &amp;lbrack；画層&amp;rbrack；不必要な再計算を減らす
* &lbrack;Layers&rbrack;クローンパッチを使用するとクラッシュする
* &lbrack;Layers&rbrack;イメージの読み込みレイヤを選択しても計算がトリガーされなくなりました
* &amp;lbrack；レイヤー&rbrack;コピーパッチおよびコンテンツに応じた塗りつぶしレイヤーが、選択時に再計算されなくなりました
* &amp;lbrack；チャンネル設定&amp;rbrack；使用を有効または無効にするとレンダリングがトリガーされるようになりました
* &lbrack;Resources&rbrack;ライブラリ内のスタックを一括クリックする際にフリーズを防止
* &lbrack;Resources&amp;rbrack；以前に追加したリンクされたフォルダーを再度追加すると、パフォーマンスが低下します
* &lbrack;Resources&amp;rbrack；削除された。sbsar ファイルを開こうとした際のクラッシュを修正しました
* &lbrack;Performance&rbrack;パラメータにアクセスするためにマテリアルをロードしない
* &lbrack;Performance&rbrack;プロジェクトまたはオーサリングされたマテリアルで使用されている場合にのみ、アセットをバックアップする
* &amp;lbrack；書き出し&amp;rbrack；書き出しキューの固定マテリアルがスキップされたり、間違ったパラメーターで書き出されることがある
* &lbrack;2D ビュー&amp;rbrack；復元されたパンとズーム
* &lbrack;Content&amp;rbrack；寄木パターンはAmbient occlusionチャンネルを考慮します
* &lbrack;Content&rbrack; ペイント – カスタムマスクを有効にしたときにマスク入力を表示
* &lbrack;Content&rbrack; Stonewall Pattern - 法線マップの縞模様を除去します。
* &lbrack;Content&rbrack; Height変調 – 2dビューの二重base colorのエントリを修正する

**既知の問題：**

* 高解像度で、コンテンツに応じた塗りつぶしフィルターの処理が遅い
* 1つのマテリアルに複数の区切り記号を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）のクラッシュを喜ばせる
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます

## バージョン1

### 1.1.4 (2019.1.4)ゴマ

*（リリース：2020年1月30日）*

**追加：**

* &lbrack;Resources&rbrack;リソースフォルダをクリアする際の確認プロンプト

**修正済み：**

* &amp;lbrack；レイヤー&rbrack;レイヤーを上下の2つ以上のレイヤーに移動
* &lbrack;Create&amp;rbrack；良好なパフォーマンスを得るのに十分なVRAMバジェットの配分

**既知の問題：**

* 大量のリソースを読み込むと、Substance Alchemistが低下することがあります
* 高解像度で、コンテンツに応じた塗りつぶしフィルターの処理が遅い
* 1つのマテリアルに複数の区切り記号を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）のクラッシュを喜ばせる
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます
* macOSで「Heightに垂直」フィルターがクラッシュすることがある

### 1.1.3 (2019.1.3)ゴマ

*（リリース：2020年1月28日）*

**追加：**

* &amp;lbrack；ワークフロー&amp;rbrack；複数のワークフローのサポート
* &amp;lbrack；ワークフロー&rbrack; PBR 光沢度ワークフローのサポート
* &amp;lbrack；ワークフロー&amp;rbrack；新規チャンネル設定パネル
* &amp;lbrack；ワークフロー&rbrack;プロジェクト作成時のワークフロー選択
* &amp;lbrack；チャンネル設定&amp;rbrack；特定のチャンネル計算をアクティブ化/非アクティブ化
* &amp;lbrack；チャンネル設定&amp;rbrack；現在のマテリアルで使用可能なカスタムチャンネルのリストを表示
* &amp;lbrack；チャンネル設定&amp;rbrack；必要に応じてカスタムチャンネルを自動計算
* &amp;lbrack；チャンネル設定&rbrack;カスタムチャンネルの計算を強制/ブロック
* &lbrack;Layers&rbrack; Atlas Scatterおよびスプラッタフィルタ内のマテリアル入力プレースホルダの新しいUI
* &amp;lbrack；レイヤー&rbrack;フィルターの画像入力パラメーターは、レイヤーの下に取り込むことができます
* &lbrack;Layers&amp;rbrack；一部のレイヤーが最新でない場合に通知を表示
* &lbrack;Layers&amp;rbrack；通知を介して古いレイヤーの最新バージョンに更新する可能性
* &lbrack;Project&rbrack;プロジェクト作成時の新しいメタデータフィールド
* &lbrack;Inspire&amp;rbrack；生成されたバリエーションはプロジェクト固有です
* &lbrack;2D ビュー&rbrack;レイヤ入力、レイヤ出力、およびマテリアル出力を切り替え
* &lbrack;Welcome Screen&rbrack; Add Import project (.alch)オプション
* &lbrack;Preferences&rbrack;キャッシュの場所とAnalyticsのプライバシー設定を行うための新しいPreferencesウィンドウ
* &lbrack;UI&amp;rbrack；新規UIボタン
* &amp;lbrack；パフォーマンス&amp;rbrack；並列化システムの全体的な改善
* &lbrack;Performance&rbrack; マテリアルの計算数の最適化
* &lbrack;エンジン&rbrack; Substance engineの更新
* &amp;lbrack；フレームワーク&rbrack; Qt 5.13にアップグレード
* &lbrack;MacOS&rbrack; macOS Catalinaサポートの全体的な機能強化
* &lbrack;Content&amp;rbrack；調整フィルタ – 法線の強度と反転のパラメータ

**修正済み：**

* &amp;lbrack；レイヤー&rbrack;レイヤーを削除するときにイメージ入力パラメーターを設定解除
* &lbrack;Layers&rbrack;コピーパッチレイヤーを追加する際のクラッシュを修正する
* &lbrack;Layers&rbrack;レイヤーマテリアルを他のレイヤースタックマテリアルでブレンドする際のクラッシュを修正
* &amp;lbrack；書き出し&amp;rbrack；書き出し用のチャンネル選択が優先されるようになりました
* &lbrack;Resources&rbrack;リソースパネルでナビゲーション中にクラッシュしない
* &lbrack;Resources&amp;rbrack；破損したSubstanceファイルを読み込む際のクラッシュを修正
* &lbrack;Resources&amp;rbrack；大きなフォルダーを読み込む際のクラッシュ数を減らす
* &lbrack;Thumbnail&rbrack; Thumbnail 計算でインターフェイスがフリーズしない
* &amp;lbrack；画像の読み込み&rbrack;アプリケーション全体でサポートされる画像タイプの統一
* &lbrack;Preset&rbrack; SBSARからプリセットを作成するときに説明を保存する
* &lbrack;Inspire&amp;rbrack；画像のドラッグ&amp;ドロップを修正
* &lbrack;Application&amp;rbrack；終了時にクラッシュを修正
* &lbrack;Application&rbrack; マテリアルの書き出し時に終了時にクラッシュを修正する
* &lbrack;UI&amp;rbrack；の修正と改善
* &lbrack;UI&amp;rbrack；一時マテリアルを「未保存のアセット」に名前変更
* &lbrack;Content&amp;rbrack；すべてのフィルタのグローバル更新とクリーニング

**既知の問題：**

* 大量のリソースを読み込むと、Substance Alchemistが低下することがあります
* 高解像度で、コンテンツに応じた塗りつぶしフィルターの処理が遅い
* 1つのマテリアルに複数の区切り記号を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）のクラッシュを喜ばせる
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます
* macOSで「Heightに垂直」フィルターがクラッシュすることがある

### 1.1.2 (2019.1.2)ゴマ

*（リリース：2019年12月11日）*

**追加：**

* &lbrack;Layers&rbrack; SaveとSave asのオプションには、レイヤースタックツールバーのインタフェースからアクセスできます。
* フォルダー間を移動するためのリソースパネルの&amp;lbrack；リソース&rbrack;クリアなブレッドクラム
* &lbrack;Resources&amp;rbrack；上のすべてのフォルダにアクセスするために戻るボタンを押したままにする
* &lbrack;Resources&amp;rbrack；読み込んだマテリアルの再読み込みを追加オプションを使用して最新バージョンに更新
* &lbrack;Layers&rbrack; Image import layerで画像を変更する可能性
* &lbrack;Layers&rbrack;イメージをチャンネルとして定義できます（base color、法線、Height、...） 画像読み込みレイヤーで
* &lbrack;Content&rbrack;Substance Sourceから新しいアトラスエレメントを散乱するための新しいAtlas Scatterフィルター
* &amp;lbrack；コンテンツ&amp;rbrack；新しいオイルペイント効果フィルター
* &lbrack;Content&rbrack; New Channels Generation filter :base colorや法線マップからHeight、ambient occlusion、ラフネスを生成

**修正済み：**

* &lbrack;UI&rbrack; [画層スタック]ツールバーのツールチップを再アクティブ化
* &lbrack;UI&rbrack;スライダー値に2桁の小数点以下を入力する際の問題を修正
* &lbrack;Performance&rbrack; マテリアルをすばやく切り替えるときのクラッシュを修正
* &amp;lbrack；書き出し&amp;rbrack；書き出しの終了前に別のマテリアルに切り替えてもクラッシュしない
* &lbrack;Resources&rbrack;コンテキストメニューは、右クリックするとマテリアルの上に表示されます
* &lbrack;Layers&rbrack; レイヤースタックが空のときに「ここをクリック」リンクが機能しています
* &amp;lbrack；プリセット&rbrack; Alchemistで作成したマテリアルの場合、ツイークパネルの「保存」ボタンを削除
* &lbrack;Tweak&rbrack; Alchemistで作成されたマテリアルの場合に表示される情報メッセージ
* &lbrack;ビューポート&rbrack; Specular levelテクスチャのデフォルト値が0.04に修正される
* &amp;lbrack；ファイルメニュー&rbrack; 「保存して別名で保存」オプションの修正と名前変更
* &lbrack;エンジン&amp;rbrack；読み込み時に一部のSBSARファイルのクラッシュを防ぐために、Substanceエンジンのバージョンを更新します。
* &lbrack;Content&rbrack; タイリングフィルターがambient occlusionチャンネルで機能しています
* &lbrack;Content&amp;rbrack；切り抜きフィルターがambient occlusionチャンネルで機能しています
* &lbrack;Content&rbrack; Water filter modifers gain the 高さマップ
* &lbrack;Content&amp;rbrack；不透明度描画モードのトップマテリアルのタイリングを修正
* &amp;lbrack；一番上のマテリアルのContent&amp;rbrack；のHeightが不透明度描画モードで保持される
* &lbrack;Content&amp;rbrack；穿孔フィルターにカスタムマスク、カスタムパターン、拡大・縮小マップを追加できます
* &lbrack;Content&rbrack; Height変調フィルタは、Heightと法線マップを16ビットに強制します。
* &lbrack;Content&amp;rbrack；補正フィルターにより、Heightと法線マップが16ビットに強制されます。

**既知の問題：**

* 大量のリソースを読み込むと、Substance Alchemistが低下することがあります
* 高解像度で、コンテンツに応じた塗りつぶしフィルターの処理が遅い
* 1つのマテリアルに複数の区切り記号を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）のクラッシュを喜ばせる
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます
* macOSで「Heightに垂直」フィルターがクラッシュすることがある

### 1.1.1 (2019.1.1)ゴマ

*（リリース：2019年11月26日）*

**追加：**

* &lbrack;ブレンド&amp;rbrack；新しい不透明度ブレンドモード
* &lbrack;エンジン&amp;rbrack；新しいSubstance engineバージョン

**修正済み：**

* &lbrack;Layers&amp;rbrack；まだ計算中のレイヤーを削除中にクラッシュが発生しました
* &amp;lbrack；レイヤー&amp;rbrack；一番下のレイヤーの削除中にクラッシュを修正(&amp;R)
* &lbrack;Layers&rbrack; マテリアル名に特殊文字が含まれている場合にクラッシュを修正する
* &lbrack;Layers&rbrack;ウィジェットを使用するすべてのフィルターの計算を停止
* &lbrack;Layers&rbrack; クローンパッチとコンテンツに応じた塗りつぶしフィルターの使用時にクラッシュが発生しないようにする
* &lbrack;Layers&rbrack;スプラッタ入力スロットでフィルタをドラッグアンドドロップ中にクラッシュを修正(&amp;R)
* &lbrack;Resources&rbrack;ローカルフォルダーのリンク時またはSubstance Alchemistへのリソースの読み込み時に発生するクラッシュの修正
* &lbrack;Collection&rbrack;マテリアルを迅速に切り替える際のクラッシュを修正
* &lbrack;UI&amp;rbrack；値がNULLであるか、ビューポート上のタイリングやディスプレイスメントのスライダーで無効であるときに、クラッシュを修正
* &lbrack;Inspire&rbrack; 「Inspire」タブへのアクセス中のクラッシュを修正
* &lbrack;Inspire&amp;rbrack；保存されたばかりのレイヤースタック素材にインスピレーションを与えているときにクラッシュする問題を修正
* &lbrack;Performance&rbrack;ヘビーSubstanceマテリアルとフィルター（タイリング）の処理速度が向上
* &lbrack;Help&rbrack;エクスポートログファイルを修正
* &lbrack;Content&rbrack; Randomizerフィルタはすべてのチャネルで動作
* &lbrack;Content&rbrack;マルチアングルのワークフローでは、すべてのスキャンが考慮されます
* &amp;lbrack；コンテンツ&rbrack; AOブレンド正しいブレンド
* &lbrack;Content&amp;rbrack；曲線ブレンド正しいブレンド
* &amp;lbrack；コンテンツ&rbrack;カラーIDブレンド補正ブレンド
* &lbrack;Content&rbrack; Custom Mask Blend correct blend
* &lbrack;Content&rbrack;ラフネス修正用の補正フィルターを修正
* &lbrack;Content&rbrack;カスタム通常チャンネルアップロード用のベースマテリアルフィルタを修正
* &lbrack;Content&rbrack; Fix Custom Import pattern of the Embossing filter

**既知の問題：**

* 1つのマテリアルに複数の区切り文字を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）でDelighterがクラッシュする
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます
* 「通常からHeight」フィルターは、MacOSでクラッシュする可能性があります

### 1.1.0(2019.1.0)ごま

*（リリース：2019年11月4日）*

**追加：**

* &amp;lbrack；プロジェクト&rbrack;プロジェクトの作成
* &lbrack;Project&rbrack;プロジェクトデータを含む.alchファイル形式の概要
* &amp;lbrack；プロジェクト&rbrack;コレクションとそのマテリアルを含む.alchプロジェクトを書き出す
* &amp;lbrack；プロジェクト&rbrack; .alchプロジェクトの読み込み
* &amp;lbrack；プロジェクト&amp;rbrack；最近使用したプロジェクトを開く
* &amp;lbrack；ようこそ画面&amp;rbrack；起動時にようこそ画面が表示されます
* &amp;lbrack；ようこそ画面&amp;rbrack；ようこそ画面からプロジェクトを作成
* &amp;lbrack；ようこそ画面&amp;rbrack；ようこそ画面ですべてのプロジェクトのリストにアクセスする
* &amp;lbrack；ようこそ画面&rbrack;ドキュメントにアクセスするためのクイックリンク，ポップアップとライセンス管理について
* &amp;lbrack；ファイルメニュー&rbrack;ファイルメニューの統合
* &amp;lbrack；ファイルメニュー&rbrack; 「ファイル」タブからプロジェクトコマンドにアクセスし、レイヤースタックを保存
* &amp;lbrack；ファイルメニュー&rbrack; 「編集」タブから「取り消し」コマンドと「やり直し」コマンドにアクセス
* &amp;lbrack；ファイルメニュー&amp;rbrack；以前のヘルプメニューは、「ヘルプ」タブの下のファイルメニューに移動しました
* &amp;lbrack；画層&rbrack; レイヤースタックの新しいアーキテクチャ
* &amp;lbrack；画層&rbrack; レイヤースタックの新しいUI
* &amp;lbrack；レイヤー&rbrack;ツールバーで描画モードを直接選択
* &amp;lbrack；画層&rbrack;ブレンドパラメータとマテリアルパラメータに個別にアクセス
* &amp;lbrack；レイヤー&rbrack; レイヤースタックのスプラッターフィルターの専用入力に直接マテリアルを追加する
* &amp;lbrack；レイヤー&rbrack;イメージの読み込みレイヤーでスキャン順序を直接変更
* &lbrack;ビューポート&rbrack; カメラ視野の制御
* &lbrack;ビューポート&rbrack;正投影モードと遠近法カメラの切り替えが可能
* &lbrack;ビューポート&amp;rbrack；各チャンネルの表示解像度とビット深度情報
* &lbrack;Resources&rbrack; ベースマテリアルはデフォルトで開かれています
* &lbrack;Cache&rbrack;サムネールキャッシュフォルダーを見つける
* &lbrack;Cache&rbrack;レンダーキャッシュフォルダを検索する
* &amp;lbrack；パネル&rbrack;マテリアル設定パネルが一時的に非表示になる
* &lbrack;Workflow&rbrack; Specular/光沢が一時的に無効になっています
* &lbrack;MacOS&rbrack; Catalina OSバージョン公証
* &lbrack;Content&rbrack; Delighterフィルターの新しいバージョン
* &amp;lbrack；コンテンツ&amp;rbrack；新規画像コンテンツに応じた塗りつぶしフィルター
* &amp;lbrack；コンテンツ&amp;rbrack；新規マテリアルコンテンツに応じた塗りつぶしフィルター
* &lbrack;Content&rbrack;変形フィルターには安全な変形オプションがあります

**修正済み：**

* 新しいUIおよびアーキテクチャリリースでは、作成に関連する以前のすべてのバグは現在無効です
* ツールヒントでトップバーのアイコンが非表示にならない(3D、2D、2D/3D)
* &lbrack;Content&rbrack; Splatter filter accepts Atlas with complete Heightマップ
* &lbrack;Content&rbrack; Transform filter works on images (scan1, scan2,...)

**既知の問題：**

* 1つのマテリアルに複数の区切り文字を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）でDelighterがクラッシュする
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます
* 「通常からHeight」フィルターは、MacOSでクラッシュする可能性があります

## ベータ版

### 0.8.1-βキヌア

*（リリース：2019年8月19日）*

**追加：**

* ランチャーからプロジェクトSubstance AlchemistにSubstance Sourceアセットを送信する機能

**修正済み：**

* &lbrack;Create&amp;rbrack；一部のフィルターはクイックアクセサーにリストされていますが、フィルターパネルにはリストされていません
* &lbrack;MacOS&amp;rbrack；終了時のクラッシュを修正

**既知の問題：**

* 1つのマテリアルに複数の区切り文字を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）でDelighterがクラッシュする
* Delighterステージをすばやく表示トグルすることはお勧めしません
* 画像読み込みレイヤーのプロパティパネルにTIF画像が表示されない
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます
* macOSで「Heightに垂直」フィルターがクラッシュすることがある
* macOSで終了時に引き続きランダムにクラッシュする可能性がある

### 0.8.0 – ベータキヌア

*（リリース：2019年8月8日）*

**追加：**

* &lbrack;Resources&rbrack; マテリアルフォルダをローカルディスクに接続してミラーリングする
* &lbrack;Resources&rbrack; マテリアルフォルダーとそのサブフォルダーを参照
* &lbrack;Resources&amp;rbrack；別のウィンドウでマテリアルリソースパネルを切り離し、リソースをフルスクリーンで表示
* &lbrack;Resources&rbrack; New Resources panelフォルダとサブフォルダのナビゲーションをサポートするためのレイアウト
* &lbrack;Resources&rbrack; breadcrumを使用してフォルダ内を移動
* &lbrack;Resources&rbrack;ローカルフォルダーの同期を、右クリックでアクセス可能な「同期」オプションで強制的に実行
* &amp;lbrack；リソース&amp;rbrack；右クリックでアクセス可能な「切断」オプションを使用してローカルフォルダーを切断
* &amp;lbrack；管理&rbrack;Substanceファイルの埋め込みタグを表示
* &amp;lbrack；管理&rbrack; マテリアルのタグを追加、編集、削除
* &lbrack;マテリアルを管理&amp;rbrack；評価
* &amp;lbrack；画層&rbrack;パノラマ出力をサポート
* &lbrack;Layers&rbrack; Image Importレイヤでイメージ入力を削除できます
* &amp;lbrack；画層&amp;rbrack；新しく追加された画層の自動選択
* &lbrack;Layers&rbrack;レイヤ削除後の下のレイヤの自動選択
* &lbrack;UX&amp;rbrack；別のラボに切り替えるときに左パネルを表示したままにする(&amp;R)
* &lbrack;UX&amp;rbrack；空でないレイヤースタックーに画像を読み込む際に、ベースレイヤーを作成しないか、マテリアルワークフローポップアップを開かない
* &lbrack;UI&amp;rbrack；新規テキストフィールドスタイル
* &lbrack;UI&amp;rbrack；新しい検索ボックススタイル
* &lbrack;UI&amp;rbrack；新規パネルヘッダースタイル
* &lbrack;UI&amp;rbrack；新しいビジーインジケータースタイル
* &lbrack;UI&rbrack; New Layers スタック背景スタイル
* &lbrack;UI&rbrack; Adobe Cleanフォントを使用
* &lbrack;UI&rbrack;カラー入力パラメーターのスポイトアイコンのプレースホルダーを削除
* &lbrack;Performance&rbrack; Busy indicator optimization
* &lbrack;Content&rbrack; New Pattern Generator filter
* &lbrack;Content&rbrack; New Blur filter

**修正済み：**

* &lbrack;Inspire&rbrack; 10色を超える色を使用しているときにクラッシュを修正
* &lbrack;2D ビュー&rbrack; 2D ビューのチャンネルリストのスクロールバーを修正
* &lbrack;Viewer&rbrack; 2 環境マップの非出力を読み込む際のクラッシュを修正(&amp;R)
* &lbrack;Content&rbrack;エンボスおよび穿孔フィルターのカスタムパターンに対するPNG読み込みを修正
* &amp;lbrack；書き出し&amp;rbrack；標準およびHeight 16ビット/チャンネル書き出しを修正
* 同じ名前の2つのプリセットを持つマテリアルを読み込む際に無限ループが発生する
* ベースマテリアルレイヤーでの長いファイルパスの表示の修正

**既知の問題：**

* 1つのマテリアルに複数の区切り文字を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）でDelighterがクラッシュする
* Delighterステージをすばやく表示トグルすることはお勧めしません
* 画像読み込みレイヤーのプロパティパネルにTIF画像が表示されない
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます
* macOSで「Heightに垂直」フィルターがクラッシュすることがある
* macOSで終了時にランダムにクラッシュすることがある

### 0.7.0 – ベータペッパー

*（リリース：2019年6月13日）*

**追加：**

* &amp;lbrack；フィルター&rbrack;スペースバーを押すと、フィルターにすばやくアクセスできます
* &amp;lbrack；フィルター&rbrack;フィルターを管理、参照、および読み込みするための新しい専用パネル
* &amp;lbrack；メタデータ&rbrack;メタデータを表示するマテリアルを右クリック
* &amp;lbrack；メタデータ&rbrack;ディスク上の場所を確認するには、マテリアルを右クリックします。
* &amp;lbrack；スライダー&rbrack; Ctrlキーを押してホバーするとスライダーがアニメーション化される
* &amp;lbrack；スライダー&rbrack; Pキーを押してスライダーアニメーションを停止し、再起動します
* &lbrack;Export&rbrack; SBSAR書き出しはSubstance Sourceのガイドラインに従います
* &lbrack;License&amp;rbrack；環境変数を使用してSubstance Alchemistをアクティブ化
* &lbrack;UX&rbrack;ファイルダイアログは、最後に選択したファイルパスを記憶します。
* &lbrack;UX&rbrack;フォルダダイアログは、最後に選択されたフォルダパスを記憶します
* &lbrack;UI&rbrack; [リソースを更新]パネルUI
* &lbrack;UI&amp;rbrack；検索バーのUIを更新
* &lbrack;UI&amp;rbrack；新規マテリアルを作成アイコンが更新されました
* &lbrack;Help&rbrack; URLがsubstance3d.comドメインに更新されます
* &lbrack;メッシュ&amp;rbrack；布メッシュが使用可能になりました
* &lbrack;Content&rbrack; New Corrosion Filter
* &lbrack;Content&rbrack; New Oxydation Filter
* &amp;lbrack；コンテンツ&amp;rbrack；新規モスフィルター
* &lbrack;Content&amp;rbrack；新規Dustフィルタ
* &lbrack;Content&rbrack; New Brickwall pattern Filter
* &amp;lbrack；コンテンツ&amp;rbrack；新規ストーンウォールパターンフィルター
* &amp;lbrack；コンテンツ&amp;rbrack；新規木目仕上げフィルタ
* &lbrack;Content&rbrack; New Metal Finish Filter
* &lbrack;Content&amp;rbrack；新規Snowフィルタ
* &lbrack;Content&amp;rbrack；新規ランダマイザーフィルター
* &lbrack;Content&rbrack;ベースマテリアルフィルターに直接テクスチャを読み込めるようになりました

**修正済み：**

* レイヤースタック保存時のクラッシュの修正
* 環境回転スライダーで1より大きい値を追加できます
* ブレンドレイヤーをブレンドレイヤーからマテリアルレイヤーに前後に変形する場合は、ブレンドパラメータが失われないようにしてください
* 同じレイヤースタックのバリエーションを複数回生成する場合の重複の修正
* マテリアルを再び開くと、Alchemistはスライダーの変更された範囲（最小および最大）を記憶します

**既知の問題：**

* 1つのマテリアルに複数の区切り記号を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）のクラッシュを喜ばせる
* Delighterステージをすばやく表示トグルすることはお勧めしません
* カスタム環境の読み込みが黒になることがある
* 画像読み込みレイヤーのプロパティパネルにTIF画像が表示されない
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます
* macOSで「Heightに垂直」フィルターがクラッシュすることがある

### 0.6.1 – ベータオレンジ

*（リリース：2019年6月13日）*

**追加：**

* &lbrack;エンジン&amp;rbrack；最新のSubstance DesignerSubstance engineとの互換性を確保するためのバージョンアップデート(&amp;r)
* &lbrack;License&amp;rbrack；初めてインストールする場合のライセンスフォルダーの更新
* &lbrack;Layers&rbrack; レイヤースタックでいつでも再読み込みしてカスタムフィルターを更新

**修正済み：**

* &lbrack;Data Compatibility&rbrack;アップグレード時のデータ破損を制限するための予防修正(&amp;L)

**既知の問題：**

* 1つのマテリアルに複数の区切り文字を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）でDelighterがクラッシュする
* Delighterステージをすばやく表示トグルすることはお勧めしません
* カスタム環境の読み込みが黒になることがある
* 画像読み込みレイヤーのプロパティパネルにTIF画像が表示されない
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます

### 0.6.0 – ベータオレンジ

*（リリース：2019年4月18日）*

**追加：**

* &amp;lbrack；メタデータ&amp;rbrack；専用のタブでマテリアルメタデータを表示および入力
* &lbrack;Collection&amp;rbrack；検索結果から直接コレクションを作成
* &amp;lbrack；メディアパブリッシング&rbrack;コレクションの掲示板の書き出し
* &lbrack;UX&rbrack; Ctrl+Zキーを押して、微調整の変更または画像の読み込みを取り消す
* &lbrack;UX&rbrack; Ctrl+Shift+Zを押して、微調整の変更または画像の読み込みをやり直す
* &lbrack;UI&amp;rbrack；新しいスタイルを持つ新しいアイコン
* &lbrack;Performance&rbrack;タブの切り替えをより適切に処理するための新しいセッションマネージャー
* &amp;lbrack；パフォーマンス&rbrack;イメージの読み込みレイヤーをすばやく開く
* &lbrack;Content&rbrack; New Metal汎用マテリアル
* &amp;lbrack；コンテンツ&amp;rbrack；新規マテリアル
* &lbrack;Content&rbrack; New Stone汎用マテリアル
* &lbrack;Content&rbrack; Embossing filter update
* &amp;lbrack；コンテンツ&amp;rbrack；刺繍フィルターの更新
* &lbrack;Content&rbrack; ペイントフィルタの更新
* &lbrack;Content&rbrack; Delighter filter update

**修正済み：**

* &lbrack;Content&rbrack; Water filter is working in the Specular/光沢度ワークフロー
* アクティベーションポップアップの「グレースケール」ラジオボタンを修正
* コーマキャラクターを含むファイルを承認
* ポップアップウィンドウでの小さなフォントの問題の修正
* 一部のNVIDIAカードのFXAAパラメーターとの競合による透明UIの問題を修正
* スライダーに値を入力した後にフィールドのフォーカスを解除する
* クラッシュを軽減するために、VRAMの最小容量をdelighterに割り当てます
* アプリケーションウィンドウのサイズ変更時にウィンドウがフリーズする
* 評価中にレイヤースタックが削除されたときのクラッシュを修正しました

**既知の問題：**

* 1つのマテリアルに複数の区切り記号を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）のクラッシュを喜ばせる
* Delighterステージをすばやく表示トグルすることはお勧めしません
* カスタム環境の読み込みが黒になることがある
* 画像読み込みレイヤーのプロパティパネルにTIF画像が表示されない
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます

### 0.5.4 – ベータ名町

*（リリース：2019年3月26日）*

**修正済み：**

* &amp;lbrack；スプラッタレイヤを削除する際のスタック&rbrack;クラッシュ
* &lbrack;Data&rbrack;アセットデータベースがアプリケーションクラッシュ時に破損する
* &lbrack;Data&rbrack; Substance Alchemistは、資産データベースが破損していると開始できません
* マテリアルを読み込む際のランダムなクラッシュ

**既知の問題：**

* 1つのマテリアルに複数の区切り記号を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）のクラッシュを喜ばせる
* Delighterステージの高速表示の切り替えは、パフォーマンスに影響します
* カスタム環境の読み込みが黒になることがある
* 画像読み込みレイヤーのプロパティパネルにTIF画像が表示されない
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます
* 保存先の既定のコレクションは空にすることができます

### 0.5.3 – ベータ名町

*（リリース：2019年3月19日）*

**追加：**

* リソースパネルでのマテリアル名による検索
* &lbrack;UI&rbrack;クローンツールブラシサイズ可視化を使用した新しいUI
* &lbrack;UI&amp;rbrack；非表示ステージの選択と削除(&amp;R)
* &lbrack;UI&amp;rbrack；新規テキストフィールドUI
* &amp;lbrack；ヘルプ&rbrack; Substance Source、Substance share、Substanceアカデミーのwebサイトにアクセス
* &lbrack;Content&rbrack;ジェネレータとアトラスを含む新しいデフォルトマテリアル
* &lbrack;Content&rbrack;ビットマップからマテリアルへの更新
* &lbrack;Content&rbrack; Dirtの更新
* &lbrack;Content&rbrack; 錆の更新
* &lbrack;Content&rbrack; New Embossing filter
* &lbrack;Content&rbrack; New Embroidery filter
* &amp;lbrack；コンテンツ&amp;rbrack；新規浸食フィルター
* &amp;lbrack；コンテンツ&amp;rbrack；新しい砂利ジェネレータ
* &amp;lbrack；コンテンツ&amp;rbrack；新規ペイントフィルター
* &lbrack;Content&rbrack; New Parquet Pattern filter
* &amp;lbrack；コンテンツ&amp;rbrack；新しい舗装パターンフィルタ
* &lbrack;Content&amp;rbrack；新しい穿孔フィルター
* &lbrack;Content&rbrack; New Splatter filter
* &amp;lbrack；コンテンツ&amp;rbrack；新しいテキスタイルウェアフィルター
* &lbrack;Content&amp;rbrack；新しい変形フィルター

**修正済み：**

* &lbrack;ビューポート&amp;rbrack；球メッシュ、X上のタイリングx2
* &amp;lbrack；独自のビューポートを読み込む際の環境&rbrack; クラッシュ
* &lbrack;ビューポート&rbrack;環境マップは露光量値も使用するようになりました
* &lbrack;ビューポート&rbrack; F ショートカットがカメラ角度をリセットしない
* &lbrack;Export&rbrack; SBS export works with latest Substance Designer 2018.3.3
* &lbrack;Export&rbrack; SBSAR書き出しはマテリアルと同じガイドラインに従います
* &lbrack;UI&rbrack;スクロールバーをドラッグ可能
* フォルダーおよびファイルパスでは、特殊文字がサポートされています
* マテリアルを保存すると、サムネールが再生成される

**既知の問題：**

* 1つのマテリアルに複数の区切り記号を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）のクラッシュを喜ばせる
* Delighterステージの高速表示の切り替えは、パフォーマンスに影響します
* カスタム環境の読み込みが黒になることがある
* 画像読み込みレイヤーのプロパティパネルにTIF画像が表示されない
* スライダーに特定の値を入力するときは、昏睡やポイントを無視することができます
* 保存先の既定のコレクションは空にすることができます

### 0.5.2 – ベータ名町

*（リリース：2019年3月7日）*

**追加：**

* ハイプロファイルGPUの検出と使用

**修正済み：**

* 回転パラメーターに適切なスライダーウィジェットがある
* マテリアルをドラッグ&amp;ドロップする際の青い線の表示を修正
* マテリアルを最初のレイヤーの下にドロップする際のマテリアルブレンドの補正
* カスタム画像のパスが設定されていない場合にのみプラグ画像が入力される

**既知の問題：**

* ファイルパスに特殊文字が含まれていると、マテリアルを保存できない
* 1つのマテリアルに複数の区切り記号を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）のクラッシュを喜ばせる
* Delighterステージの高速表示の切り替えは、パフォーマンスに影響します
* 独自の環境を読み込み中のクラッシュ

### 0.5.1 – ベータ名町

*（リリース：2019年3月4日）*

**修正済み：**

* クラッシュレポート、バグレポート、ライセンスポップアップの修正

**既知の問題：**

* 1つのマテリアルに複数の区切り記号を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）のクラッシュを喜ばせる
* Delighterステージの高速表示の切り替えは、パフォーマンスに影響します
* 独自の環境を読み込み中のクラッシュ

### 0.5.0 – ベータ名町

*（リリース：2019年2月28日）*

**追加：**

* &lbrack;レイヤースタック&rbrack;レイヤの並べ替え
* &lbrack;レイヤースタック&amp;rbrack；非表示レイヤーを削除
* &lbrack;レイヤースタック&rbrack; マテリアルを任意の場所に直接読み込む
* &lbrack;レイヤースタック&amp;rbrack；新しいフィルタパラメータタイプとしてのマテリアル入力
* &amp;lbrack；パフォーマンス&rbrack;Substance engineの予算は、パフォーマンス向上のために動的です。
* &amp;lbrack；パフォーマンス&amp;rbrack；特にMacOSでのOpenGLパフォーマンスの向上(&amp;r)
* &lbrack;Data&amp;rbrack；新しいバージョンがリリースされた後のデータのアップグレードの高速化
* Windows 7およびWindows 8で利用可能な&lbrack;Content&rbrack; AI Delighter
* &lbrack;Content&rbrack; AI Delighter available on RTX GPU

**修正済み：**

* アプリケーション終了時に発生する可能性のあるクラッシュを修正
* 大きなコレクションを書き出す場合に、書き出しポップアップを開く速度が速くなる

**既知の問題：**

* 1つのマテリアルに複数の区切り記号を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）のクラッシュを喜ばせる
* Delighterステージの高速表示の切り替えは、パフォーマンスに影響します
* 独自の環境を読み込み中のクラッシュ

### 0.4.0-βマフィン

*（リリース：2019年1月17日）*

**追加：**

* &amp;lbrack；書き出し&rbrack;コレクションのSubstanceアーカイブ(sbsar)書き出し
* &amp;lbrack；書き出し&rbrack;コレクションのSubstanceファイル(sbs)書き出し
* &amp;lbrack；書き出し&amp;rbrack；書き出しパネルに表示される書き出しキュー
* &lbrack;Export&amp;rbrack；書き出す前にコレクションまたはマテリアルに名前を付ける
* &lbrack;Data&rbrack; Ctrl+Shift+Sを押してマテリアルとして保存
* &lbrack;Data&rbrack; Ctrl+Sを押してマテリアルを保存
* &lbrack;Data&rbrack;コレクションとマテリアルは、複数のバージョン間で互換性があります
* &lbrack;Data&amp;rbrack；最新のフィルターでレイヤースタックを更新
* &lbrack;Data&amp;rbrack；読み込んだカスタムフィルターのホットリロード
* &lbrack;UI&amp;rbrack；計算中のビューポートのビジュアルフィードバック
* &lbrack;UI&amp;rbrack；新規ボタンスタイル
* &lbrack;UI&amp;rbrack；保存ポップアップにアクティブなコレクションの名前を表示
* &lbrack;UI&rbrack;イメージの読み込みレイヤのソースイメージを修正
* &lbrack;Content&rbrack; Custom usages are supported
* &lbrack;Content&amp;rbrack；その他の画像入力パラメーターが画像形式でサポートされています。
* &lbrack;Content&rbrack; Make It Tile Advancedという名前の新しいタイリングフィルタ
* &lbrack;Content&rbrack; Update of the Water filter

**修正済み：**

* ビットマップからマテリアルへの変換は、Specular/光沢度ワークフローを処理します

**既知の問題：**

* 1つのマテリアルに複数の区切り記号を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）のクラッシュを喜ばせる
* DelighterはRTX GPUカードではサポートされていません
* Delighterステージの高速表示の切り替えは、パフォーマンスに影響します

### 0.3.1-βラザニア

*（リリース：2018年12月17日）*

**修正済み：**

* 抽出された10色のクラッシュでカラーバリエーションを作成
* 保存したばかりのクラッシュでカラーバリエーションを作成
* Substance Alchemistのバージョン更新ポップアップのリンクが正しくない

**既知の問題：**

* ビットマップからマテリアルへの変換がSpecular/ラフネスワークフローに対応していない
* 1つのマテリアルに複数の区切り記号を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）のクラッシュを喜ばせる
* Delighterステージの高速表示の切り替えは、パフォーマンスに影響します

### 0.3.0-βラザニア

*（リリース：2018年12月12日）*

**追加：**

* &amp;lbrack；書き出し&amp;rbrack；新規書き出しポップアップ
* &lbrack;Export&rbrack;コレクション全体を書き出す
* &amp;lbrack；書き出し&rbrack;ビットマップを任意の形式で書き出す
* &amp;lbrack；書き出し&rbrack;ビットマップを任意の解像度で書き出す
* &amp;lbrack；書き出し&amp;rbrack；任意のチャンネルのみを書き出す
* &lbrack;Export&amp;rbrack；書き出しの見積サイズをプレビューする
* &amp;lbrack；書き出し&amp;rbrack；書き出す前に、ディスクで使用可能なサイズをプレビューします
* &lbrack;UX&rbrack;コレクションのアクション（右クリックでアクセス可能）
* &lbrack;UX&rbrack; Inspireで画像またはアセットの設定を解除できるようにします
* &lbrack;UX&rbrack; Substance Alchemistが最大起動されている
* &lbrack;Assets&rbrack; マテリアルを次のバージョンで永続的に保存するための新しい保存方法
* &amp;lbrack；ヘルプ&rbrack;ヘルプメニューからオンラインドキュメントにアクセス
* &amp;lbrack；パフォーマンス&rbrack; Substance Alchemistで作成した複雑なマテリアルのカラーバリエーションを高速化
* &lbrack;Performance&rbrack; ラボの切り替え時のメモリリークを低減
* &lbrack;Content&rbrack;スケールチェッカーによるマテリアルの物理サイズの診断(&amp;R)
* &lbrack;Content&rbrack; Update Italien Venice Mosaicタイルマテリアル
* &lbrack;Content&rbrack; Mossスプラッタを更新

**修正済み：**

* マテリアルの保存時にデフォルト名が不要
* マテリアルを保存してSubstance Alchemistを再度開くと、フィルタパラメータが失われる
* &amp;lbrack；コンテンツ&rbrack; AOと曲率のブレンドの下から上へのロジックを修正

**既知の問題：**

* 以前のバージョンで作成されたマテリアルは、新しいバージョンでは使用できません。
* ビットマップからマテリアルへの変換がSpecular/粗さのワークフローに対応していない
* 1つのマテリアルに複数の区切り文字を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）でDelighterがクラッシュする
* Delighterステージの高速表示の切り替えは、パフォーマンスに影響します

### 0.2.0 – ベータキウイ

*（リリース：2018年11月9日）*

**追加：**

* ビューアの設定はセッション間で保存されます
* マテリアル設定はセッション間で保存されます
* プロパティパネルの高速読み込み
* &lbrack;Log&rbrack;ヘルプメニューからログファイルをエクスポート
* &lbrack;UI&amp;rbrack；新規スライダースタイル
* &lbrack;UI&amp;rbrack；プリセットと調整パネルを統合
* &lbrack;UI&amp;rbrack；新規サムネールスタイル
* ビューポートから直接アクセスできるディスプレイスメント、タイリング、シャドウの設定
* &amp;lbrack；コンテンツ&amp;rbrack；新規デフォルトマテリアル
* &lbrack;Content&rbrack; Moss Splatterアップデート
* &lbrack;Framework&rbrack; Substance engineフレームワークを更新

**修正済み：**

* ラボの切り替えによるレイヤースタックの削除が修正されました
* ビューポートに表示されるロード時間の値が正しい
* マテリアルワークフローのデフォルトチャンネルが正しく初期化されている
* カスタムメッシュの読み込みを無効にする
* ビットマップ書き出し
* &lbrack;MacOS&amp;rbrack；終了Substance Alchemistに「強制終了」が必要な場合がある

**既知の問題：**

* 以前のバージョンで作成されたマテリアルは、新しいバージョンでは使用できません。
* 1つのマテリアルに複数の区切り文字を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）でDelighterがクラッシュする
* Delighterステージの高速表示の切り替えは、パフォーマンスに影響します

### 0.1.1-beta版ジャム

*（リリース：2018年10月24日）*

**追加：**

* BaseColor Delighterが利用可能になりました
* 「ヘルプ」メニューからSubstance Alchemist情報にアクセスする
* 新しいバージョンのSubstance Alchemistが利用可能になったときに通知を受け取る
* Windowsでコンソールが表示されなくなった
* 新規サムネールスタイル
* &lbrack;MacOS&rbrack; Substance Alchemistをフルスクリーンで設定可能
* &lbrack;Filter&rbrack; Import Custom maskを使用して2つのマテリアル間のブレンドを管理
* &amp;lbrack；フィルタ&rbrack;コケのスケールを制御
* &lbrack;Filter&rbrack; クローンパッチの更新

**修正済み：**

* パラメーターリストの画像入力に画像を追加すると、出力が更新されます
* カスタムフィルターの読み込みで、黒のAmbient occlusion度と不透明度が追加されない

**既知の問題：**

* 以前のバージョンで作成されたマテリアルは、新しいバージョンでは使用できません。
* &lbrack;MacOS&amp;rbrack；終了Substance Alchemistに「強制終了」が必要な場合がある
* 1つのマテリアルに複数の区切り記号を使用することはお勧めしません
* 古いNVIDIAドライバー（400.x未満）のクラッシュを喜ばせる
* Delighterステージの高速表示の切り替えは、パフォーマンスに影響します
* マテリアル書き出し缶クラッシュ

### 0.1.0-βアイスクリーム

*（リリース：2018年10月17日）*

**追加：**

* 4種類のブレンドを使用したブレンド（Heightブレンド、サンプルブレンド、曲率ブレンド、AOブレンド）
* キャッシュ・メカニズムを導入してレイヤースタックの再計算を最適化
* ビューポート内の贈り物にインスパイアしたマテリアルの自動選択
* マテリアル設定パネルに一元化された標準形式
* 切り抜きとタイリングウィジェットのコントロール(-90xB0,+90xB0, make square,...) 掃除
* 新規Snowフィルター

**修正済み：**

* パネルUIクリーニング
* ウィンドウやパネルのサイズを変更すると、ビューポートがちらつく
* 保存時にレイヤースタックが再計算されない
* インターフェイスで名前を付けるアセットは、グラフ名ではなくラベルを使用します

**既知の問題：**

* レイヤーの表示をすばやく切り替えて、画像を引き伸ばす
* フォーカスでカメラの角度がリセットされる
