---
title: "INodeIterator.NextNode"
second_title: "Aspose.SVG for .NET API 参考"
description: "INodeIterator NextNode 方法。返回集合中的下一个节点并将迭代器在集合中的位置前进。创建 NodeIterator 后，第一次调用 nextNode 将返回集合中的第一个节点。"
type: docs
weight: 40
url: /zh/net/aspose.svg.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

返回集合中的下一个节点并将迭代器在集合中的位置前移。创建 NodeIterator 后，第一次调用 nextNode() 将返回集合中的第一个节点。

```csharp
public Node NextNode()
```

### 返回值

在被迭代的集合中下一个节点，如果该集合中没有更多成员，则为 null。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR：如果在调用 detach 方法之后调用此方法，则会抛出此错误。 |

### 另请参阅

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
