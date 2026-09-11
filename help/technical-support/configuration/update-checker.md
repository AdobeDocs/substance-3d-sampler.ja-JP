---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/technical-support/configuration/update-checker.html"
breadcrumb-title: ''
description: Substance 3D Samplerのアップデートチェッカーを使用して、新しいバージョンやリリースノートの情報を常に受け取る方法について説明します。
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Configuration > Update Checker
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 更新チェッカー
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '162'
ht-degree: 0%

---


# 更新チェッカー

更新ウィンドウは、新しいバージョンのSubstance Alchemistが利用可能かどうかを示し、最新の[リリースノート](../../release-notes/release-notes.md)も表示されます。

このウィンドウは、新しいバージョンをダウンロードできる場合に、Substance Alchemistを起動すると自動的に表示されます。

次の方法を使用すると、起動時にこのウィンドウが表示されないようにすることができます。

* ウィンドウの「次のバージョンまで通知しない」設定を使用して、次のバージョンまでウィンドウの表示を一時的にスキップします。
* 編集/環境設定/アップデートを確認で「**アップデートを確認**」設定を無効にする
* コマンドライン&#x200B;**—skip-version-check**&#x200B;を使用して、Substance Alchemistの起動時に新しいバージョンのアプリケーションが利用可能かどうかを確認しません
* 環境変数&#x200B;**SUBSTANCE\_ALCHEMIST\_SKIP\_CHECK\_FOR\_UPDATES**:Value 0または1を使用する（1 =更新チェックを無効にする）

>[!NOTE]
>
> Substance Alchemist 2020.1(2.1)以降でサポート
