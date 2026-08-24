---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Aspose.SVG for .NET API 参考"
description: "INodeIterator PointerBeforeReferenceNode 属性。此标志的值决定迭代器是否可见实体引用节点的子节点。如果为 false，则这些子节点及其后代将被排除。请注意，此排除优先于 whatToShow 和过滤器。还需注意，这目前是 NodeIterator 可能拒绝整个子树而不是跳过单个节点的唯一情况。若要生成实体引用已展开且不暴露实体引用节点本身的文档视图，请在创建迭代器时使用 whatToShow 标志隐藏实体引用节点并将 expandEntityReferences 设置为 true。若要生成包含实体引用节点但不进行实体展开的文档视图，请使用 whatToShow 标志显示实体引用节点并将 expandEntityReferences 设置为 false。"
type: docs
weight: 10
url: /zh/net/aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

此标志的值决定实体引用节点的子节点是否对迭代器可见。如果为 false，它们及其后代将被拒绝。请注意，此拒绝优先于 whatToShow 和过滤器。还要注意，这目前是 NodeIterators 可能拒绝整个子树而不是跳过单个节点的唯一情况。要生成一个实体引用已展开且不暴露实体引用节点本身的文档视图，请使用 whatToShow 标志隐藏实体引用节点，并在创建迭代器时将 expandEntityReferences 设置为 true。要生成一个包含实体引用节点但不进行实体展开的文档视图，请使用 whatToShow 标志显示实体引用节点，并将 expandEntityReferences 设置为 false。

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` 如果 [expand entity references]；否则为 `false`。

### 另请参阅

* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
