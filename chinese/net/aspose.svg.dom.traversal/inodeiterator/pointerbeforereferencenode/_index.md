---
title: PointerBeforeReferenceNode
second_title: Aspose.SVG for .NET API 参考
description: 该标志的值确定实体 引用节点的子节点是否对迭代器可见如果为假他们和 他们的后代将被拒绝请注意此拒绝将 优先于 whatToShow 和过滤器还要注意 这是目前 NodeIterators 可能拒绝完整子树而不是 跳过单个节点的唯一情况 要生成具有实体引用 展开且不暴露实体引用节点本身的文档视图请使用 whatToShow 标志隐藏实体引用节点 并在创建 迭代器时将 expandEntityReferences 设置为 true要生成具有实体引用 节点但没有实体扩展的文档视图请使用 whatToShow 标志 来显示实体引用节点并将 expandEntityReferences 设置为 false
type: docs
weight: 10
url: /zh/net/aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

该标志的值确定实体 引用节点的子节点是否对迭代器可见。如果为假，他们和 他们的后代将被拒绝。请注意，此拒绝将 优先于 whatToShow 和过滤器。还要注意 ，这是目前 NodeIterators 可能拒绝完整子树而不是 跳过单个节点的唯一情况。 要生成具有实体引用 展开且不暴露实体引用节点本身的文档视图，请使用 whatToShow 标志隐藏实体引用节点 并在创建 迭代器时将 expandEntityReferences 设置为 true。要生成具有实体引用 节点但没有实体扩展的文档视图，请使用 whatToShow 标志 来显示实体引用节点并将 expandEntityReferences 设置为 false。

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### 适当的价值

` true` if [展开实体引用]；否则，` false` 。

### 也可以看看

* interface [INodeIterator](../../inodeiterator)
* 命名空间 [Aspose.Svg.Dom.Traversal](../../inodeiterator)
* 部件 [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
