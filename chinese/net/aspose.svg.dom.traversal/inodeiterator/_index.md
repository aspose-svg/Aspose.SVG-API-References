---
title: INodeIterator
second_title: Aspose.SVG for .NET API 参考
description: 迭代器用于遍历一组节点例如 NodeList 中的 节点集由 特定节点管理的文档子树查询的结果或任何其他节点集 要迭代的节点集由 NodeIterator 的 实现确定 DOM Level 2 为文档子树的文档顺序 遍历指定了一个 单个 NodeIterator 实现这些迭代器的实例是通过调用 DocumentTraversal .createNodeIterator 创建的 
type: docs
weight: 1260
url: /zh/net/aspose.svg.dom.traversal/inodeiterator/
---
## INodeIterator interface

迭代器用于遍历一组节点，例如 NodeList 中的 节点集，由 特定节点管理的文档子树，查询的结果，或任何其他节点集 。要迭代的节点集由 NodeIterator 的 实现确定。 DOM Level 2 为文档子树的文档顺序 遍历指定了一个 单个 NodeIterator 实现。这些迭代器的实例是通过调用 DocumentTraversal .createNodeIterator() 创建的 。

另见[文档对象模型(DOM) 2 级遍历和范围规范](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113) 。 @since DOM Level 2

```csharp
public interface INodeIterator : ITraversal
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode) { get; } | 该标志的值确定实体 引用节点的子节点是否对迭代器可见。如果为假，他们和 他们的后代将被拒绝。请注意，此拒绝将 优先于 whatToShow 和过滤器。还要注意 ，这是目前 NodeIterators 可能拒绝完整子树而不是 跳过单个节点的唯一情况。 要生成具有实体引用 展开且不暴露实体引用节点本身的文档视图，请使用 whatToShow 标志隐藏实体引用节点 并在创建 迭代器时将 expandEntityReferences 设置为 true。要生成具有实体引用 节点但没有实体扩展的文档视图，请使用 whatToShow 标志 来显示实体引用节点并将 expandEntityReferences 设置为 false。 |
| [ReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/referencenode) { get; } | 当前参考节点。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Detach](../../aspose.svg.dom.traversal/inodeiterator/detach)() | 将 NodeIterator 从它迭代 的集合中分离出来，释放所有计算资源并将迭代器 置于 INVALID 状态。调用分离后， 对 nextNode 或 previousNode 的调用将 引发异常 INVALID_STATE_ERR。 |
| [NextNode](../../aspose.svg.dom.traversal/inodeiterator/nextnode)() | 返回集合中的下一个节点，并提升集合中 迭代器的位置。创建 NodeIterator 后， 对 nextNode() 的第一次调用会返回 集合中的第一个节点。 |
| [PreviousNode](../../aspose.svg.dom.traversal/inodeiterator/previousnode)() | 返回集合中的前一个节点并将 NodeIterator 在集合中的位置向后移动。 |

### 也可以看看

* interface [ITraversal](../itraversal)
* 命名空间 [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal)
* 部件 [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->