---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/pipeline-and-integrations/hp-z-captis-support/known-issues-and-limitations-hp-z-captis-support.html"
breadcrumb-title: ''
description: Substance 3D SamplerでHP Z Captisを使用する際の既知の問題と制限事項を確認して、現在の制限事項と回避策を理解します。
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 既知の問題、制限事項、HPZ Captisサポート
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '215'
ht-degree: 0%

---


# 既知の問題と制限事項

<b>バージョン：Sampler 6.0、2026年4月16日リリース</b>

* HP Z Captisワークフローを使用したSamplerは、現時点ではWindowsでのみ使用できます。

* スキャンの実行中にデバイスを物理的に取り外しても、キャプチャは停止しません。 キャプチャ中にデバイスの接続が切断された場合は、30秒待ってから再接続して、進行中のキャプチャセッションに再接続できるようにします。
* 現在書き出されている5つのマップは、[ベースカラー]、[粗さ]、[法線]、[Height]、[不透明度]です。
* キャプチャ中にウィンドウを閉じると、入力されたメタデータが失われます。
* USB経由でCaptisからデータを転送しているときに「コンテンツを参照」または「シャットダウン」ボタンのいずれかをクリックすると、転送が停止します。

* TDRの問題がある場合は、Sustance Painterの[このドキュメントページ](https://experienceleague.adobe.com/en/docs/substance-3d-painter/using/technical-support/technical-issues/gpu-issues/gpu-drivers-crash-with-long-computations-tdr-crash)を参照してください。このページが問題の修正に役立ちます。
* デバイス内部のライブフィードを見る代わりに「プレビュー」の手順がすべて黒になっている場合は、レンズキャップをデバイスのコーン内部から取り外したことを確認してください。
