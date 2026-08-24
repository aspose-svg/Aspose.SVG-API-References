---
title: "Node.AppendChild"
second_title: "Aspose.SVG for .NET API 参考"
description: "Node AppendChild 方法。将节点添加到指定父节点的子节点列表末尾。如果给定的 child 是文档中已有节点的引用，AppendChild 会将其从当前位置移动到新位置，无需先将节点从其父节点中移除再追加到其他节点。"
type: docs
weight: 170
url: /zh/net/aspose.svg.dom/node/appendchild/
---
## Node.AppendChild method

将节点添加到指定父节点的子节点列表末尾。如果给定的 child 是文档中已有节点的引用，`AppendChild` 会将其从当前位移到新位置（无需先将节点从其父节点中移除再追加到其他节点）。

这意味着一个节点不能同时出现在文档的两个位置。因此，如果节点已经有父节点，则会先将其移除，然后再追加到新位置。可以使用[`CloneNode`](../clonenode/) 方法在将节点追加到新父节点之前创建其副本。使用[`CloneNode`](../clonenode/) 创建的副本不会自动保持同步。

```csharp
public Node AppendChild(Node node)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | Node | 要追加到给定父节点（通常是元素）的节点。 |

### 返回值

追加的子节点的 Node，除非 child 是 [`DocumentFragment`](../../documentfragment/)，此时返回空的 [`DocumentFragment`](../../documentfragment/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| DOMException | 当违反 DOM 树约束时抛出此异常。 |

### 另请参阅

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
