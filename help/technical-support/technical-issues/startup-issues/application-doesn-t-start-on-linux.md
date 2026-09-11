---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/technical-support/technical-issues/startup-issues/application-doesn-t-start-on-linux.html"
breadcrumb-title: ''
description: LinuxでSubstance 3D Samplerを起動する際の問題を修正し、アプリケーションの起動に関する問題やエラーメッセージを解決する方法について説明します。
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Technical Issues > Startup issues > Application doesnt start on Linux
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Linuxでアプリケーションが起動しない
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '108'
ht-degree: 0%

---


# アプリケーションがLinuxで起動しない

ターミナルで次のエラーメッセージが表示されると、Linux上でアプリケーションが起動しないことがあります。

```
error while loading shared libraries: libicui18n.so.50
```


これは、ライブラリICU ([International Components for Unicode](http://site.icu-project.org/))が見つからないか、インストールされているバージョンが新しすぎることを意味します。 アプリケーションにはバージョン50が必要です。

この問題を解決するには、パッケージマネージャーからバージョン50をインストールするか、または&#x200B;**/usr/lib64**&#x200B;にインストールするときに、見つからないバージョンを[手動でダウンロード](http://mirror.centos.org/centos/7/os/x86_64/Packages/libicu-50.2-4.el7_7.x86_64.rpm)します。
