---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/interface/preferences/normal-format.html"
breadcrumb-title: ''
description: Substance 3D Samplerで法線マップ形式の環境設定を行い、DirectX形式とOpenGL形式を切り替える方法について説明します。
helpx_creative_field: ""
helpx_description: Sampler > Interface > Preferences > Normal Format
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 法線の形式
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '118'
ht-degree: 5%

---


# 法線の形式

通常のマップは、<b>DirectX</b>形式を使用して処理されます。通常の形式の設定を変更して、OpenGL形式をインポートおよびエクスポートするには、<b> OpenGL</b>ワークフローを維持してください。

*既定： DirectX*

通常の形式の環境設定は、次の影響を受けます。

* 画像の読み込みレイヤー
* 書き出し

## 画像の読み込みレイヤー

法線テクスチャを読み込むと、法線フォーマットは環境設定で選択したフォーマットに設定されます。

### 書き出し

#### SBSARおよびSBS

normal形式は公開パラメータです。 このパラメータは、必要な形式で法線を生成するように、ホストアプリケーションによって微調整できます。

#### 画像形式

法線は、環境設定で選択した形式で書き出されます。
