---
title: "IDocumentTraversal.CreateNodeIterator"
second_title: "Aspose.SVG for .NET API 参考"
description: "IDocumentTraversal CreateNodeIterator 方法。创建一个以指定节点为根的子树上的新 NodeIterator。"
type: docs
weight: 10
url: /zh/net/aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/)*) {#createnodeiterator}

在指定节点为根的子树上创建一个新的 NodeIterator。

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| root | Node | 将与其子节点一起迭代的节点。迭代器最初位于该节点之前。设置此位置时，不考虑 whatToShow 标志和 filter（如果有）。根不能为空。 |

### 返回值

新创建的 NodeIterator。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR：如果指定的 root 为 null，则抛出此错误。 |

### 另请参阅

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/), long*) {#createnodeiterator_1}

在指定节点为根的子树上创建一个新的 NodeIterator。

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| root | Node | 将与其子节点一起迭代的节点。迭代器最初位于该节点之前。设置此位置时，不考虑 whatToShow 标志和 filter（如果有）。根不能为空。 |
| whatToShow | Int64 | 标志指定哪些节点类型可以出现在迭代器呈现的树的逻辑视图中。请参阅 NodeFilter 的描述以获取可能的 SHOW_ 值集合。这些标志可以使用 OR 进行组合。 |

### 返回值

新创建的 NodeIterator。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR：如果指定的 root 为 null，则抛出此错误。 |

### 另请参阅

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/), long, [INodeFilter](../../inodefilter/)*) {#createnodeiterator_2}

在指定节点为根的子树上创建一个新的 NodeIterator。

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| root | Node | 将与其子节点一起迭代的节点。迭代器最初位于该节点之前。设置此位置时，不考虑 whatToShow 标志和 filter（如果有）。根不能为空。 |
| whatToShow | Int64 | 标志指定哪些节点类型可以出现在迭代器呈现的树的逻辑视图中。请参阅 NodeFilter 的描述以获取可能的 SHOW_ 值集合。这些标志可以使用 OR 进行组合。 |
| filter | INodeFilter | 用于此 TreeWalker 的 NodeFilter，或为 null 以表示没有过滤器。 |

### 返回值

新创建的 NodeIterator。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR：如果指定的 root 为 null，则抛出此错误。 |

### 另请参阅

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
