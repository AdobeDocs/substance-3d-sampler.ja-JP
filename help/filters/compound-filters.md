---
helpx_url: 'https://helpx.adobe.com/jp/substance-3d-sampler/filters/compound-filters.html'
breadcrumb-title: ''
description: Substance 3D Samplerで複合フィルターを作成および使用し、複数のフィルターを組み合わせて1つの再利用可能なレイヤーを作成する方法を説明します。
helpx_creative_field: ''
helpx_description: Sampler > Filters > Compound Filters
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: 複合フィルター
user-guide-description: ''
user-guide-title: ''
source-git-commit: dc832dc546735437051226f4e1e731b55147b3ea
workflow-type: tm+mt
source-wordcount: '603'
ht-degree: 0%

---


# 複合フィルター

この機能を使用すると、インターフェイスで1つのレイヤーとして表示され、複数のフィルターで構成される新しいタイプのフィルターを作成できます。

>[!NOTE]
>
> Substance 3D Sampler 3.1.0以降でサポート

## 説明

複合フィルターは、**.ssapfilter**&#x200B;ファイルで、次の。7zip圧縮フォルダーです：

* json形式を使用した説明ファイル： **myfilter\_name.json**
* **resources**&#x200B;フォルダーには、次の情報が含まれています：
  * フィルターサムネール： icon.png
  * 外部ファイルの依存関係

### 説明ファイルの内容

* 名前：インターフェイスに表示される複合フィルターのラベル
* Id：複合フィルターの一意の識別子
* カテゴリ：アセットをカテゴリ別にグループ化する場合に、アセットパネルで使用する複合フィルターのカテゴリ
* バージョン：複合フィルターのバージョンを定義する増分番号。
* Node：使用するノードのリスト
* リンク：異なるノード間の接続のリスト

### 例

```JSON
{ "SamplerFilter":  
 { 
 "Name": "My filter", 
 "Category": "My filter category", 
 "Id": "my_unique_id", 
 "Version": 2, 
 "Node": [ 
        { 
            "Id": "foo", 
            "InternalFilter": "Foo" 
        }, 
        { 
            "Id": "bar", 
            "File": "bar.sbsar" 
        } 
    ], 
    "Link": [ 
        { 
            "From": { "Node": "FilterInput", "Usage": "baseColor" }, 
            "To": { "Node": "foo", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "FilterInput", "Usage": "normal" }, 
            "To": { "Node": "foo", "Usage": "normal"} 
        }, 
        { 
            "From": { "Node": "foo", "Usage": "baseColor" }, 
            "To": { "Node": "bar", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "bar", "Usage": "baseColor" }, 
            "To": { "Node": "FilterOutput", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "foo", "Usage": "normal" }, 
            "To": { "Node": "FilterOutput", "Usage": "normal"} 
        } 
    ] 
}}
```

## 手順を追った作成

1. 新しいファイルを作成します： **my\_new\_filter.json**
1. 名前、ID、カテゴリを定義する…
1. 必要なノードのリストを定義します
1. 外部ファイルが必要な場合は、**.json**&#x200B;の横に&#x200B;**resources**&#x200B;フォルダーを作成します
1. **resources**&#x200B;フォルダーにファイルを追加
1. ノード間のリンクのリストを書き込みます
1. JSONが有効であることを確認します（入力ミスがないこと、カンマがないこと、ブラケットが欠落していること）
1. サムネイルが必要な場合は、**resources**&#x200B;フォルダーに画像&#x200B;**icon.png**&#x200B;を追加します
1. **.json**&#x200B;ファイルと&#x200B;**resources**&#x200B;フォルダーを選択し、7zip圧縮します

## ドキュメント

### バージョン

バージョン番号を使用すると、異なるイテレーションを追跡できます。 以前のバージョンの複合フィルターで完了したレイヤースタックを開くと、最新バージョンにアップグレードするように勧める通知が表示されます。

### ノード

ノードは、Substance 3D Samplerの内部フィルターを参照できます。 ノードと内部フィルター&#x200B;**InternalFilter**&#x200B;のラベルの間のリンクを定義するために使用される一意の識別子&#x200B;**Id**&#x200B;を定義します

```JSON
{ 
  "Id": "step1_identifier", 
  "InternalFilter": "Dirt" 
}
```

ノードは、Substance 3D SamplerにないSBSARファイルを参照できます。 ノードとSBSARファイルのファイル名&#x200B;**File**&#x200B;の間のリンクの定義に使用する一意の識別子&#x200B;**Id**&#x200B;を定義します。 SBSARファイルは、.alchfilterファイルの横の&#x200B;**resources**&#x200B;フォルダーにある必要があります。

```JSON
{ 
  "Id": "step1_identifier", 
  "File": "foo.sbsar" 
}
```

>[!NOTE]
>
> **filterImg**&#x200B;および&#x200B;**filterMat**&#x200B;はノードIDとして使用できません

### リンク

リンクは、2つのノードがどのようにリンクされ、2つの要素で構成されているかを表します。

* From:ノードで使用される使用方法
* To:ノードの使用状況の出力

各エレメントには3つの属性があります。

* Node：使用するノードの&#x200B;**Id**&#x200B;を宣言します
  * 複合フィルターの入力を設定します。ノードIDは&#x200B;**FilterInput**&#x200B;です
  * 複合レイヤーの出力を設定します。ノードIDは&#x200B;**FilterOutput**&#x200B;です
* 使用法：使用する使用法を宣言します。 次の3つのオプションがあります。
  * 一度に1つだけ使用して、リンクによってリンクを宣言します（baseColor、normal、Height、ambientOcclusion、ラフネス、metallic、diffuse、Specular、glossiness、specularLevel、不透明度、エミッシブ、scan1、...）
  * リスト[&quot;baseColor&quot;, &quot;normal&quot;]を指定することもできます。 **From**&#x200B;の一覧の最初の項目は、**To**&#x200B;の一覧の最初の項目と一致します。 その他
  * **\***を使用すると、Substance 3D Samplerで開始ノードと終了ノードのすべての使用箇所を一致させることができます（**\***を別のリンクと組み合わせることはできません。また、同じノード間で1つのリンクとリストリンクを使用することができます）
* グループ：ノードが同じ使用方法の数倍を持つ場合、グループ属性を使用して特定の使用方法を選択できます。 例：描画フィルターでは、下部のマテリアルのbaseColorを&#x200B;*Material1*&#x200B;を使用して、上部のマテリアルのbaseColorを&#x200B;*Material2*&#x200B;を使用します

```JSON
Link between two nodes  
{ 
  "From": { "Node": "node1","Usage": "baseColor", "Group": ""}, 
  "To": { "Node": "node2", "Usage": "baseColor"} 
} 
 
Link between outputs of layers below of the compound filter and the compound filter: 
{ 
  "From": { "Node": "FilterInput", "Usage": "*" }, 
  "To": { "Node": "node1", "Usage": "*"} 
} 

Link to declare outputs of the compound filter: 
{ 
  "From": { "Node": "node1", "Usage": "*" }, 
  "To": { "Node": "FilterOutput", "Usage": "*"} 
}
```
