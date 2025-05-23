---
title: INodeIterator.PreviousNode
second_title: Aspose.SVG for .NET API Reference
description: INodeIterator PreviousNode method. Returns the previous node in the set and moves the position of the NodeIterator backwards in the set
type: docs
weight: 50
url: /net/aspose.svg.dom.traversal/inodeiterator/previousnode/
---
## INodeIterator.PreviousNode method

Returns the previous node in the set and moves the position of the NodeIterator backwards in the set.

```csharp
public Node PreviousNode()
```

### Return Value

The previous Node in the set being iterated over, or null if there are no more members in that set.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: Raised if this method is called after the detach method was invoked. |

### See Also

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
