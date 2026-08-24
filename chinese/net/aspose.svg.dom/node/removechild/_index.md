---
title: "Node.RemoveChild"
second_title: "Aspose.SVG for .NET API 参考"
description: "Node RemoveChild 方法。从 DOM 中移除子节点并返回被移除的节点"
type: docs
weight: 270
url: /zh/net/aspose.svg.dom/node/removechild/
---
## Node.RemoveChild method

从 DOM 中移除一个子节点并返回被移除的节点。

注意：只要对被移除的子节点保持引用，它仍然存在于内存中，但不再是 DOM 的一部分。它仍然可以在代码中稍后重复使用。如果 `RemoveChild` 的返回值未被存储，且没有其他引用保留，它将在短时间后自动从内存中删除。

```csharp
public Node RemoveChild(Node child)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| child | Node | 一个将从 DOM 中移除的子节点的 [`Node`](../)。 |

### 返回值

不同于 [`CloneNode`](../clonenode/)，返回值会保留与其关联的 [`EventListener`](../../../aspose.svg.dom.events/ieventlistener/) 对象。

### 另请参阅

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
