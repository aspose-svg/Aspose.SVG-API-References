---
title: Node.RemoveChild
second_title: Aspose.SVG for .NET API Reference
description: Node RemoveChild method. Removes a child node from the DOM and returns the removed node
type: docs
weight: 270
url: /net/aspose.svg.dom/node/removechild/
---
## Node.RemoveChild method

Removes a child node from the DOM and returns the removed node.

Note: As long as a reference is kept on the removed child, it still exists in memory, but is no longer part of the DOM. It can still be reused later in the code. If the return value of `RemoveChild` is not stored, and no other reference is kept, it will be automatically deleted from memory after a short time.

```csharp
public Node RemoveChild(Node child)
```

| Parameter | Type | Description |
| --- | --- | --- |
| child | Node | A [`Node`](../) that is the child node to be removed from the DOM. |

### Return Value

Unlike [`CloneNode`](../clonenode/) the return value preserves the [`EventListener`](../../../aspose.svg.dom.events/ieventlistener/) objects associated with it.

### See Also

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
