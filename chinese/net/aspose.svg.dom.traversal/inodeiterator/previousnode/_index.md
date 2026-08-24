---
title: "INodeIterator.PreviousNode"
second_title: "Aspose.SVG for .NET API 参考"
description: "INodeIterator PreviousNode 方法。返回集合中的前一个节点并将 NodeIterator 在集合中的位置向后移动。"
type: docs
weight: 50
url: /zh/net/aspose.svg.dom.traversal/inodeiterator/previousnode/
---
## INodeIterator.PreviousNode method

返回集合中的上一个节点并将 NodeIterator 在集合中的位置后移。

```csharp
public Node PreviousNode()
```

### 返回值

在被迭代的集合中之前的节点，如果该集合中没有更多成员，则为 null。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR：如果在调用 detach 方法之后调用此方法，则会抛出此错误。 |

### 另请参阅

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
