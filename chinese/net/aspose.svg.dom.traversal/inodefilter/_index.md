---
title: "INodeFilter 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Traversal.INodeFilter 接口。过滤器是能够过滤节点的对象。如果向 NodeIterator 或 TreeWalker 提供了 NodeFilter，它将在返回下一个节点之前应用该过滤器。如果过滤器接受该节点，遍历逻辑将返回它；否则遍历会寻找下一个节点，并假装被拒绝的节点不存在。"
type: docs
weight: 3240
url: /zh/net/aspose.svg.dom.traversal/inodefilter/
---
## INodeFilter interface

过滤器是能够“过滤”节点的对象。如果为 NodeIterator 或 TreeWalker 提供了 NodeFilter，它会在返回下一个节点之前应用过滤器。如果过滤器接受该节点，遍历逻辑会返回它；否则，遍历会寻找下一个节点，并假装被拒绝的节点不存在。

DOM 不提供任何过滤器。NodeFilter 只是一个接口，用户可以实现它来提供自定义过滤器。

NodeFilters 不需要了解如何在节点之间遍历，也不需要了解被遍历的数据结构。这使得编写过滤器非常容易，因为它们唯一需要做的就是评估单个节点。一个过滤器可以与多种不同的遍历方式一起使用，促进代码复用。

另请参阅 [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)。@since DOM Level 2

```csharp
public interface INodeFilter
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [AcceptNode](../../aspose.svg.dom.traversal/inodefilter/acceptnode/)(*[Node](../../aspose.svg.dom/node/)*) | 测试指定节点在 TreeWalker 或 NodeIterator 的逻辑视图中是否可见。此函数将由 TreeWalker 和 NodeIterator 的实现调用；通常不会直接从用户代码调用。（如果您想使用相同的过滤器来指导自己的应用逻辑，也可以这样做。） |

### 另请参阅

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
