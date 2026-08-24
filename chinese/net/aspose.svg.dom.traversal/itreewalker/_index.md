---
title: "ITreeWalker 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Traversal.ITreeWalker 接口。TreeWalker 对象用于使用其 whatToShow 标志和（如果有）过滤器定义的文档视图来导航文档树或子树。任何使用 TreeWalker 执行导航的函数都会自动支持 TreeWalker 定义的任何视图。"
type: docs
weight: 3270
url: /zh/net/aspose.svg.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker 对象用于使用其 whatToShow 标志和过滤器（如果有）定义的文档视图来导航文档树或子树。任何使用 TreeWalker 执行导航的函数都会自动支持 TreeWalker 定义的任何视图。

从子树的逻辑视图中省略节点可能导致结构与完整、未过滤文档中的相同子树有显著差异。TreeWalker 视图中的兄弟节点在原始视图中可能是不同、相距甚远的节点的子节点。例如，考虑一个仅保留文本节点和文档根节点的 NodeFilter。在由此产生的逻辑视图中，所有文本节点将成为兄弟节点，并直接作为根节点的子节点出现，无论原始文档的结构多么深层嵌套。

另请参阅 [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)。@since DOM Level 2

```csharp
public interface ITreeWalker : ITraversal
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CurrentNode](../../aspose.svg.dom.traversal/itreewalker/currentnode/) { get; set; } | TreeWalker 当前所在的节点。对 DOM 树的更改可能导致当前节点不再被 TreeWalker 关联的过滤器接受。currentNode 也可以显式设置为任意节点，无论它是否位于根节点指定的子树内或是否会被过滤器和 whatToShow 标志接受。即使当前节点不在当前视图中，后续遍历仍相对于 currentNode 进行，通过在请求的方向上应用过滤器；如果无法进行遍历，currentNode 将保持不变。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FirstChild](../../aspose.svg.dom.traversal/itreewalker/firstchild/)() | 将 TreeWalker 移动到当前节点的第一个可见子节点，并返回该新节点。如果当前节点没有可见子节点，返回 null，并保留当前节点。 |
| [LastChild](../../aspose.svg.dom.traversal/itreewalker/lastchild/)() | 将 TreeWalker 移动到当前节点的最后一个可见子节点，并返回该新节点。如果当前节点没有可见子节点，返回 null，并保留当前节点。 |
| [NextNode](../../aspose.svg.dom.traversal/itreewalker/nextnode/)() | 将 TreeWalker 移动到相对于当前节点的文档顺序中的下一个可见节点，并返回该新节点。如果当前节点没有下一个节点，或在从 TreeWalker 的根节点向上搜索 nextNode 时，返回 null，并保留当前节点。 |
| [NextSibling](../../aspose.svg.dom.traversal/itreewalker/nextsibling/)() | 将 TreeWalker 移动到当前节点的下一个兄弟节点，并返回该新节点。如果当前节点没有可见的下一个兄弟节点，返回 null，并保留当前节点。 |
| [ParentNode](../../aspose.svg.dom.traversal/itreewalker/parentnode/)() | 移动并返回当前节点最近的可见祖先节点。如果搜索 parentNode 时尝试从 TreeWalker 的根节点向上移动，或未能找到可见的祖先节点，则此方法保持当前定位并返回 null。 |
| [PreviousNode](../../aspose.svg.dom.traversal/itreewalker/previousnode/)() | 将 TreeWalker 移动到相对于当前节点的文档顺序中的上一个可见节点，并返回该新节点。如果当前节点没有上一个节点，或在从 TreeWalker 的根节点向上搜索 previousNode 时，返回 null，并保留当前节点。 |
| [PreviousSibling](../../aspose.svg.dom.traversal/itreewalker/previoussibling/)() | 将 TreeWalker 移动到当前节点的上一个兄弟节点，并返回该新节点。如果当前节点没有可见的上一个兄弟节点，返回 null，并保留当前节点。 |

### 另请参阅

* interface [ITraversal](../itraversal/)
* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
