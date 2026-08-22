---
helpx_url: 'https://helpx.adobe.com/jp/substance-3d-sampler/getting-started/system-requirements.html'
breadcrumb-title: ''
description: ご使用のハードウェアとソフトウェアが互換性基準を満たしていることを確認するために、Substance 3D Samplerの必要システム構成を確認してください。
helpx_creative_field: ''
helpx_description: Sampler > Getting Started > System requirements
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: 必要システム構成
user-guide-description: ''
user-guide-title: ''
source-git-commit: cd61972eaf1567863dc8c3549a1c90c84ffee825
workflow-type: tm+mt
source-wordcount: '595'
ht-degree: 1%

---


# サポート対象システム

以下に、アプリケーションでサポートされているハードウェアとシステムのリストを示します。

>[!WARNING]
>
> 次のNVIDIAドライバーは、Samplerの実行中に不安定な状態になることが知られています。
>
> * 610.47
>
> これらのバージョンの使用を避けることをお勧めします。理想的には、新しいバージョンを使用するか、新しいバージョンが利用できない場合は以前のバージョンを使用します。

## Windows

|  | 最小 | おすすめ | 最適 |
| --- | --- | --- | --- |
| **OS** | Windows 11 64ビット版23H2 | Windows 11 64ビット版24H1 | Windows 11 64ビット版24H2 |
| **CPU** | Intel Core i5 AMD Ryzen 5 | Intel Core i7 AMD Ryzen 7 | Intel Core i9 AMD Ryzen 9 |
| **GPU** | NVIDIA GeForce RTX 2060 Super NVIDIA Quadro RTX 4000 AMD Radeon RX 5700 XT AMD Radeon Pro W5700 | NVIDIA GeForce RTX 3080 NVIDIA Quadro RTX A4000 AMD Radeon RX 6800 XT AMD Radeon Pro W7700 | NVIDIA GeForce RTX 4090 NVIDIA Quadro RTX 5000 Ada Generation AMD Radeon RX 7900 XTX AMD Radeon Pro W7800 |
| **VRAM** | 8 GB | 16 GB | 24 GB |
| **RAM** | 16 GB | 32 GB | 64 GB |
| **ストレージ** | 30 GBの空き容量のあるSSD | 50 GBの空き容量のあるSSD | 70 GBの空き容量のあるSSD |

### macOS

|  | 最小 | おすすめ | 最適 |
| --- | --- | --- | --- |
| **OS** | macOS 13 Ventura | macOS14ソノマ | macOS 26タホ |
| **CPU** | Apple M1 | Apple M2 Pro | Apple M4 Pro |
| **GPU** | Apple M1 | Apple M2 Pro | Apple M4 Pro |
| **RAM** | 24 GB | 32 GB | 64 GB |
| **ストレージ** | 30 GBの空き容量のあるSSD | 50 GBの空き容量のあるSSD | 70 GBの空き容量のあるSSD |

### Linux

| Enterprise | スチーム |
| --- | --- |
| RHEL 8 <br>RHEL 9 | Ubuntu 22.04 |

>[!NOTE]
>
> お使いのシステムが上記の必要システム構成を満たしていてもパフォーマンスが低下する場合は、Samplerが間違ったGPUを使用している可能性があります。
>
> NVIDIA GPUを使用している場合は、[このページの手順に従って、Samplerが使用するGPUを変更してください](../technical-support/configuration/nvidia-driver-settings.md)。

## 一般的な推奨事項

* 快適な状態で作業するには、1メガピクセルを超え、1280ピクセルを超える解像度のモニターをお勧めします。
* 多くのSubstanceアプリは、RHEL8/9との互換性をOpenSSL 1.1.1に依存しています。 新しいバージョンのOpenSSLを使用するシステムでは、手動で提供する必要があります。

## サポートされていない設定

**ウィンドウ**

* 仮想マシンはサポートされていません。
* Windows Serverはサポートされていません。

**Mac**

* 公式のApple設定のみがサポートされています。
* eGPUは現在サポートされておらず、安定性の問題がある可能性があります。

**Linux**

* Linux上のMesaドライバはサポートされていません。

**任意のプラットフォーム**

* 内蔵GPUは、x86-64(Intel、AMD)CPUではサポートされていません。
* Samplerをサードパーティ製ソフトウェアと組み合わせて使用し、Samplerによるグラフィックドライバーの呼び出しを傍受する機能はサポートされていません。 当該ソフトウェアには、以下が含まれます。
  * カラーグレーディングを適用するリシェーダなどの後処理インジェクタ、カメラエフェクト、...
  * カスタムクロスヘア、GPUパフォーマンス指標、ビデオストリーミング用スキンなどのオンスクリーンオーバーレイ

## GPUドライバーの最小バージョン

アプリケーションを問題なく実行するために必要なGPUドライバーの最小バージョンを以下に示します。 このリストは、新しいバージョンのリリースに伴って変更される場合があります。

新しいドライバーをダウンロードするには、[GPUに古いドライバーがあります](https://experienceleague.adobe.com/ja/docs/substance-3d-painter/using/technical-support/technical-issues/gpu-issues/gpu-has-outdated-drivers)を参照してください。

| OS | NVIDIA | AMD | Intel |
| --- | --- | --- | --- |
| **ウィンドウ** | GeForce 551.86 Quadro/RTX 538.33 | Radeon 23.8.1 Radeon Pro / FirePro 24.q2 | 31.0.1015590 |
| **Linux** | 525.116.04以降&#x200B;*または* 535.54.03以降 | Radeon 23.20 Pro 23.Q3 | 非対応 |

>[!NOTE]
>
> **Mac OS**&#x200B;では、GPUドライバーはオペレーティングシステム自体から提供されます。 最新のドライバーにアクセスするには、OSを最新バージョンにアップデートしてください。

## 言語

ソフトウェアインターフェイスは次の言語で使用できます。

* English
* Deutsch
* Français
* 日本語
* 韓国語
* 中文
* イタリア語
* ポルトガル語
* スペイン語
