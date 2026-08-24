---
title: "INodeFilter.AcceptNode"
second_title: "Aspose.SVG for .NET API 参考"
description: "INodeFilter AcceptNode 方法。测试指定节点是否在 TreeWalker 或 NodeIterator 的逻辑视图中可见。此函数将由 TreeWalker 和 NodeIterator 的实现调用，通常不会直接从用户代码调用。若您希望使用相同的过滤器来指导自己的应用逻辑，也可以这样做。"
type: docs
weight: 10
url: /zh/net/aspose.svg.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

测试指定节点在 TreeWalker 或 NodeIterator 的逻辑视图中是否可见。此函数将由 TreeWalker 和 NodeIterator 的实现调用；通常不会直接从用户代码调用。（如果您想使用相同的过滤器来指导自己的应用逻辑，也可以这样做。）

```csharp
public short AcceptNode(Node n)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| n | Node | 用于检查节点是否通过过滤器。 |

### 返回值

一个常量，用于确定节点是被接受、拒绝还是跳过，如上所定义。

### 另请参阅

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
