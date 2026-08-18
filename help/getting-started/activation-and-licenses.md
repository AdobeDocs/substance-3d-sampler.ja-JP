---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/getting-started/activation-and-licenses.html"
breadcrumb-title: ''
description: Substance 3D Samplerでアプリケーションの使用を開始し、すべての機能にアクセスするためのライセンスをアクティベートして管理する方法について説明します。
helpx_creative_field: ""
helpx_description: Sampler > Getting Started > Activation and licenses
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: ライセンス認証とライセンス
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '455'
ht-degree: 1%

---


# ライセンス認証とライセンス

このページでは、Samplerの使用を開始できるように、ライセンスをアクティベートして管理する方法について説明します。

## アプリケーションタイプごとのアクティベーションプロセス

アクティベーションプロセスは、Samplerをどこから購入したか、またはどこからアクセスできるかによって異なります。

| アプリケーションタイプ | アクティベーションプロセス |
| --- | --- |
| Creative Cloud デスクトップ | [HelpXドキュメント](https://helpx.adobe.com/support/substance-3d-sampler.html)の専用ページを参照してください。問題が発生した場合、[Creative Cloudのドキュメント](https://helpx.adobe.com/creative-cloud/user-guide.html)に詳細な回答が記載されている場合があります。 |
| スチーム | Steamライブラリから直接製品を起動します。 |
| Substance 3Dスタンドアロン | 以下のアクティベーションプロセスを参照してください。 |

## ライセンス認証手順

### ライセンス認証ウィザード

![](../assets/activation-wizard.png){width="350px"}

次の3つの選択肢があります。

* **この製品の評価** ：従来の体験版は利用できなくなりました。 代わりに、各Substance 3Dアプリケーションの30日間の無料体験を[ここ](https://www.adobe.com/creativecloud/3d-augmented-reality.html)から、またはCreative Cloudデスクトップから開始できます。 各体験版は他のSubstance 3Dアプリケーションから独立しているため、一度に1つずつ、または一度に試すことができます。
* **ライセンスファイルを使ってライセンス認証する**: 2022年9月30日より前に[Substance 3D Webサイト](https://store.substance3d.com/user)のアカウントページからダウンロードしたライセンスファイル(**\*.key**)を使って製品をライセンス認証します。
* **アカウントを使用したライセンス認証** ：従来のSubstanceアカウントはライセンス認証に使用できなくなりました。 [Substanceアカウントについて詳しくは、こちらを参照してください](https://helpx.adobe.com/substance-3d/unlisted/faq-end-of-life-accounts.html)。

>[!WARNING]
>
> ライセンス認証ウィザードを使用してライセンスファイルをインストールするには、Samplerを管理者として実行し、アンチウイルスを一時的に無効にしてください。

### 手動アクティベーション

**license.key**&#x200B;ファイルを次のフォルダーに置くことで、Samplerを手動でアクティベートできます。

<table data-preserve-html="true"><colgroup> <col/> <col/> <col/> <col/> </colgroup><tbody><tr><th>Platform</th><th>バージョン</th><th colspan="2">パス</th></tr><tr><td rowspan="4"><strong>Windows</strong></td><td rowspan="2"><strong>3.0</strong>以降</td><td colspan="1">アプリデータ（ローカル）</td><td colspan="1">C:\Users\[ユーザー名]\AppData\Local\Adobe\Adobe Substance 3D Sampler</td></tr><tr><td colspan="1">アプリデータ（ローミング）</td><td colspan="1">C:\Users\[ユーザー名]\AppData\Roaming\Adobe\Adobe Substance 3D Sampler</td></tr><tr><td rowspan="2">レガシー</td><td colspan="1">アプリデータ（ローカル）</td><td colspan="1">C:\Users\[ユーザー名]\AppData\Local\Allegorithmic\Substance Alchemist</td></tr><tr><td colspan="1">アプリデータ（ローミング）</td><td colspan="1">C:\Users\[ユーザー名]\AppData\Roaming\Allegorithmic\Substance Alchemist</td></tr><tr><td rowspan="2"><strong>Mac</strong></td><td colspan="1"><strong>3.0</strong>以降</td><td colspan="2">/Users/[ユーザー名]/Library/Application Support/Adobe/Adobe Substance 3D Sampler</td></tr><tr><td colspan="1">レガシー</td><td colspan="2">/Users/[ユーザー名]/Library/Application Support/Allegorithmic/Substance Alchemist</td></tr><tr><td rowspan="2"><strong>Linux</strong></td><td colspan="1"><strong>3.0</strong>以降</td><td colspan="2">/home/[ユーザー名]/.local/share/Adobe/Adobe Substance 3D Sampler</td></tr><tr><td>レガシー</td><td colspan="2">/home/[ユーザー名]/.local/share/Allegorithmic/Substance Alchemist</td></tr></tbody></table>

>[!NOTE]
>
> 上記のパスの一部のディレクトリは、デフォルトで非表示になっている場合があります。 ファイルエクスプローラーでパスを手動で入力するか、隠しファイルを表示して表示します。

>[!NOTE]
>
> ファイルの名前が&#x200B;**license.key**&#x200B;であることを確認してください。名前が指定されていない場合、アプリケーションはファイルを見つけることができません。

### 環境変数

Samplerが&#x200B;**license.key**&#x200B;ファイルをチェックする場所は、[環境変数](../pipeline-and-integrations/environment-variables.md)で上書きできます。
