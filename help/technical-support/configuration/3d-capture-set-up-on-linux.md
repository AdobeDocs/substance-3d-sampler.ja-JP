---
helpx_url: "https://helpx.adobe.com/jp/substance-3d-sampler/technical-support/configuration/3d-capture-set-up-on-linux.html"
breadcrumb-title: ''
description: Wine 8をインストールし、必要システム構成を構成して、Substance 3D Sampler用Linux上で3D キャプチャをセットアップする方法について説明します。
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Linuxでの3D キャプチャ設定
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '99'
ht-degree: 0%

---


# Linuxでの3D キャプチャ設定

Linuxで<b>3D キャプチャ</b>を使用するには、管理者アカウントで<b>Wine 8</b>をインストールする必要があります。

Ubuntu

apt-get install wine

Red Hat Enterprise Linux(RHEL 8)

sudo subscription-manager repos —enable codeready-builder-for-rhel-8-x86\_64-rpms

dnf install wine

Red Hat Enterprise Linux(RHEL 9)

sudo subscription-manager repos —enable codeready-builder-for-rhel-9-x86\_64-rpms

dnf install wine
