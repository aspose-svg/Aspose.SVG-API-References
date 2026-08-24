---
title: "INodeIterator 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Traversal.INodeIterator 接口。迭代器用于遍历一组节点，例如 NodeList 中的节点集合、特定节点管理的文档子树、查询结果或任何其他节点集合。要遍历的节点集合由 NodeIterator 的实现决定。DOM Level 2 为文档顺序遍历文档子树指定了单一的 NodeIterator 实现。这些迭代器的实例通过调用 DocumentTraversal.createNodeIterator 创建。"
type: docs
weight: 3250
url: /zh/net/aspose.svg.dom.traversal/inodeiterator/
---
## INodeIterator interface

迭代器用于遍历一组节点，例如 NodeList 中的节点集合、特定 Node 管辖的文档子树、查询结果或任何其他节点集合。要迭代的节点集合由 NodeIterator 的实现决定。DOM Level 2 为文档子树的文档顺序遍历指定了单一的 NodeIterator 实现。这些迭代器的实例通过调用 DocumentTraversal .createNodeIterator() 创建。

另请参阅 [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)。@since DOM Level 2

```csharp
public interface INodeIterator : ITraversal
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | 此标志的值决定实体引用节点的子节点是否对迭代器可见。如果为 false，它们及其后代将被拒绝。请注意，此拒绝优先于 whatToShow 和过滤器。还要注意，这目前是 NodeIterators 可能拒绝整个子树而不是跳过单个节点的唯一情况。要生成一个实体引用已展开且不暴露实体引用节点本身的文档视图，请使用 whatToShow 标志隐藏实体引用节点，并在创建迭代器时将 expandEntityReferences 设置为 true。要生成一个包含实体引用节点但不进行实体展开的文档视图，请使用 whatToShow 标志显示实体引用节点，并将 expandEntityReferences 设置为 false。 |
| [ReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/referencenode/) { get; } | 当前的引用节点。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Detach](../../aspose.svg.dom.traversal/inodeiterator/detach/)() | 将 NodeIterator 与其遍历的集合分离，释放任何计算资源并将迭代器置于 INVALID 状态。调用 detach 后，调用 nextNode 或 previousNode 将抛出异常 INVALID_STATE_ERR。 |
| [NextNode](../../aspose.svg.dom.traversal/inodeiterator/nextnode/)() | 返回集合中的下一个节点并将迭代器在集合中的位置前移。创建 NodeIterator 后，第一次调用 nextNode() 将返回集合中的第一个节点。 |
| [PreviousNode](../../aspose.svg.dom.traversal/inodeiterator/previousnode/)() | 返回集合中的上一个节点并将 NodeIterator 在集合中的位置后移。 |

### 另请参阅

* interface [ITraversal](../itraversal/)
* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
