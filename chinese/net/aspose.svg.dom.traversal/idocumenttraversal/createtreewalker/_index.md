---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "Aspose.SVG for .NET API 参考"
description: "IDocumentTraversal CreateTreeWalker 方法。创建一个以指定节点为根的子树上的新 TreeWalker。"
type: docs
weight: 20
url: /zh/net/aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/)*) {#createtreewalker}

在指定节点为根的子树上创建一个新的 TreeWalker。

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| root | Node | 用于作为 TreeWalker 根的节点。在设置此值时，不会考虑 whatToShow 标志和 NodeFilter；任何节点类型都将被接受为根节点。TreeWalker 的 currentNode 将初始化为该节点，无论其是否可见。根节点作为向上遍历文档结构的遍历方法（如 parentNode 和 nextNode）的停止点。根节点不能为空。 |

### 返回值

新创建的 TreeWalker。

### 另请参阅

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/), long*) {#createtreewalker_1}

在指定节点为根的子树上创建一个新的 TreeWalker。

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| root | Node | 用于作为 TreeWalker 根的节点。在设置此值时，不会考虑 whatToShow 标志和 NodeFilter；任何节点类型都将被接受为根节点。TreeWalker 的 currentNode 将初始化为该节点，无论其是否可见。根节点作为向上遍历文档结构的遍历方法（如 parentNode 和 nextNode）的停止点。根节点不能为空。 |
| whatToShow | Int64 | 标志指定哪些节点类型可以出现在 tree-walker 所呈现的树的逻辑视图中。请参阅 NodeFilter 的描述以获取可能的 SHOW_ 值集合。这些标志可以使用 OR 进行组合。 |

### 返回值

新创建的 TreeWalker。

### 另请参阅

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/), long, [INodeFilter](../../inodefilter/)*) {#createtreewalker_2}

在指定节点为根的子树上创建一个新的 TreeWalker。

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| root | Node | 用于作为 TreeWalker 根的节点。在设置此值时，不会考虑 whatToShow 标志和 NodeFilter；任何节点类型都将被接受为根节点。TreeWalker 的 currentNode 将初始化为该节点，无论其是否可见。根节点作为向上遍历文档结构的遍历方法（如 parentNode 和 nextNode）的停止点。根节点不能为空。 |
| whatToShow | Int64 | 标志指定哪些节点类型可以出现在 tree-walker 所呈现的树的逻辑视图中。请参阅 NodeFilter 的描述以获取可能的 SHOW_ 值集合。这些标志可以使用 OR 进行组合。 |
| filter | INodeFilter | 用于此 TreeWalker 的 NodeFilter，或为 null 以表示没有过滤器。 |

### 返回值

新创建的 TreeWalker。

### 另请参阅

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
