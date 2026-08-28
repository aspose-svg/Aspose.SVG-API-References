---
title: "Document.CreateNodeIterator"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Document CreateNodeIterator メソッド。指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。"
type: docs
weight: 900
url: /ja/net/aspose.svg.dom/document/createnodeiterator/
---
## CreateNodeIterator(*[Node](../../node/)*) {#createnodeiterator}

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
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: 指定された root が null の場合に発生します。 |

### 参照

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../node/), long*) {#createnodeiterator_1}

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
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: 指定された root が null の場合に発生します。 |

### 参照

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../node/), long, [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)*) {#createnodeiterator_2}

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
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: 指定された root が null の場合に発生します。 |

### 参照

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
