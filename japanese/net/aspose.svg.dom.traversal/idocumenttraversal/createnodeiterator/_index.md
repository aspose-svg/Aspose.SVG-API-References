---
title: "IDocumentTraversal.CreateNodeIterator"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IDocumentTraversal CreateNodeIterator メソッド。指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。"
type: docs
weight: 10
url: /ja/net/aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/)*) {#createnodeiterator}

指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| root | ノード | 子ノードとともに反復されるノード。このイテレータは最初、このノードの直前に位置付けられます。whatToShow フラグとフィルタ（存在する場合）は、この位置を設定する際には考慮されません。root は null であってはなりません。 |

### 戻り値

新しく作成された NodeIterator。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: 指定された root が null の場合に発生します。 |

### 参照

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/), long*) {#createnodeiterator_1}

指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| root | ノード | 子ノードとともに反復されるノード。このイテレータは最初、このノードの直前に位置付けられます。whatToShow フラグとフィルタ（存在する場合）は、この位置を設定する際には考慮されません。root は null であってはなりません。 |
| whatToShow | Int64 | フラグは、イテレータが提示するツリーの論理ビューに現れる可能性のあるノードタイプを指定します。可能な SHOW_ 値のセットについては NodeFilter の説明を参照してください。これらのフラグは OR を使用して組み合わせることができます。 |

### 戻り値

新しく作成された NodeIterator。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: 指定された root が null の場合に発生します。 |

### 参照

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/), long, [INodeFilter](../../inodefilter/)*) {#createnodeiterator_2}

指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| root | ノード | 子ノードとともに反復されるノード。このイテレータは最初、このノードの直前に位置付けられます。whatToShow フラグとフィルタ（存在する場合）は、この位置を設定する際には考慮されません。root は null であってはなりません。 |
| whatToShow | Int64 | フラグは、イテレータが提示するツリーの論理ビューに現れる可能性のあるノードタイプを指定します。可能な SHOW_ 値のセットについては NodeFilter の説明を参照してください。これらのフラグは OR を使用して組み合わせることができます。 |
| filter | INodeFilter | この TreeWalker で使用する NodeFilter、またはフィルタがないことを示すための null。 |

### 戻り値

新しく作成された NodeIterator。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: 指定された root が null の場合に発生します。 |

### 参照

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
