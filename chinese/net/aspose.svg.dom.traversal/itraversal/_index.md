---
title: "ITraversal 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Traversal.ITraversal 接口。迭代器用于遍历一组节点，例如 NodeList 中的节点集合、由特定节点管理的文档子树、查询结果或任何其他节点集合。要遍历的节点集合由 NodeIterator 的实现决定。DOM Level 2 为文档子树的文档顺序遍历指定了单一的 NodeIterator 实现。这些迭代器的实例通过调用 DocumentTraversal .createNodeIterator 创建。"
type: docs
weight: 3260
url: /zh/net/aspose.svg.dom.traversal/itraversal/
---
## ITraversal interface

迭代器用于遍历一组节点，例如 NodeList 中的节点集合、特定 Node 管辖的文档子树、查询结果或任何其他节点集合。要迭代的节点集合由 NodeIterator 的实现决定。DOM Level 2 为文档子树的文档顺序遍历指定了单一的 NodeIterator 实现。这些迭代器的实例通过调用 DocumentTraversal .createNodeIterator() 创建。

另请参阅 [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)。@since DOM Level 2

```csharp
public interface ITraversal : IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Filter](../../aspose.svg.dom.traversal/itraversal/filter/) { get; } | 用于筛选节点的 NodeFilter。 |
| [Root](../../aspose.svg.dom.traversal/itraversal/root/) { get; } | NodeIterator 的根节点，在创建时指定。 |
| [WhatToShow](../../aspose.svg.dom.traversal/itraversal/whattoshow/) { get; } | 此属性决定通过迭代器呈现的节点类型。可用的常量集合在 NodeFilter 接口中定义。未被 whatToShow 接受的节点将被跳过，但其子节点仍可能被考虑。请注意，此跳过优先于过滤器（如果存在）。 |

### 另请参阅

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
