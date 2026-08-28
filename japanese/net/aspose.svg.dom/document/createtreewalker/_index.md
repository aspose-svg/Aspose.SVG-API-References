---
title: "Document.CreateTreeWalker"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Document CreateTreeWalker メソッド。指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。"
type: docs
weight: 940
url: /ja/net/aspose.svg.dom/document/createtreewalker/
---
## CreateTreeWalker(*[Node](../../node/)*) {#createtreewalker}

指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| root | ノード | TreeWalker のルートとして使用されるノード。この値を設定する際、whatToShow フラグと NodeFilter は考慮されず、任意のノードタイプがルートとして受け入れられます。TreeWalker の currentNode はこのノードに初期化され、可視かどうかにかかわらず設定されます。ルートは、parentNode や nextNode など、ドキュメント構造を上方向にたどる走査メソッドの停止点として機能します。ルートは null にしてはいけません。 |

### 戻り値

新しく作成された TreeWalker。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: 指定された root が null の場合に発生します。 |

### 参照

* interface [ITreeWalker](../../../aspose.svg.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../node/), long*) {#createtreewalker_1}

指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| root | ノード | TreeWalker のルートとして使用されるノード。この値を設定する際、whatToShow フラグと NodeFilter は考慮されず、任意のノードタイプがルートとして受け入れられます。TreeWalker の currentNode はこのノードに初期化され、可視かどうかにかかわらず設定されます。ルートは、parentNode や nextNode など、ドキュメント構造を上方向にたどる走査メソッドの停止点として機能します。ルートは null にしてはいけません。 |
| whatToShow | Int64 | フラグは、ツリーワーカーが提示するツリーの論理ビューに表示できるノードタイプを指定します。可能な SHOW_ 値のセットについては NodeFilter の説明を参照してください。これらのフラグは OR 演算子で組み合わせることができます。 |

### 戻り値

新しく作成された TreeWalker。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: 指定された root が null の場合に発生します。 |

### 参照

* interface [ITreeWalker](../../../aspose.svg.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../node/), long, [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)*) {#createtreewalker_2}

指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| root | ノード | TreeWalker のルートとして使用されるノード。この値を設定する際、whatToShow フラグと NodeFilter は考慮されず、任意のノードタイプがルートとして受け入れられます。TreeWalker の currentNode はこのノードに初期化され、可視かどうかにかかわらず設定されます。ルートは、parentNode や nextNode など、ドキュメント構造を上方向にたどる走査メソッドの停止点として機能します。ルートは null にしてはいけません。 |
| whatToShow | Int64 | フラグは、ツリーワーカーが提示するツリーの論理ビューに表示できるノードタイプを指定します。可能な SHOW_ 値のセットについては NodeFilter の説明を参照してください。これらのフラグは OR 演算子で組み合わせることができます。 |
| filter | INodeFilter | この TreeWalker で使用する NodeFilter、またはフィルタがないことを示すための null。 |

### 戻り値

新しく作成された TreeWalker。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: 指定された root が null の場合に発生します。 |

### 参照

* interface [ITreeWalker](../../../aspose.svg.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
