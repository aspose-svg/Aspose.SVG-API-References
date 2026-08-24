---
title: "ITreeWalker.CurrentNode"
second_title: "Aspose.SVG for .NET API 参考"
description: "ITreeWalker CurrentNode 属性。TreeWalker 当前所在的节点。对 DOM 树的更改可能导致当前节点不再被 TreeWalker 关联的过滤器接受。currentNode 也可以显式设置为任意节点，无论该节点是否位于根节点指定的子树内，或是否会被过滤器和 whatToShow 标志接受。即使当前节点不在当前视图中，进一步的遍历仍会相对于 currentNode 进行，并在请求的方向上应用过滤器；如果无法进行遍历，currentNode 将保持不变。"
type: docs
weight: 10
url: /zh/net/aspose.svg.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

TreeWalker 当前所在的节点。对 DOM 树的更改可能导致当前节点不再被 TreeWalker 关联的过滤器接受。currentNode 也可以显式设置为任意节点，无论它是否位于根节点指定的子树内或是否会被过滤器和 whatToShow 标志接受。即使当前节点不在当前视图中，后续遍历仍相对于 currentNode 进行，通过在请求的方向上应用过滤器；如果无法进行遍历，currentNode 将保持不变。

```csharp
public Node CurrentNode { get; set; }
```

### Property Value

当前节点。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR：如果尝试将 currentNode 设置为 null 时抛出。 |

### 另请参阅

* class [Node](../../../aspose.svg.dom/node/)
* interface [ITreeWalker](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
