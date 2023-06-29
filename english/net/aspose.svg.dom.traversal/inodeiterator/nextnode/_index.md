---
title: INodeIterator.NextNode
second_title: Aspose.SVG for .NET API Reference
description: INodeIterator method. Returns the next node in the set and advances the position of the iterator in the set. After a NodeIterator is created the first call to nextNode returns the first node in the set
type: docs
weight: 40
url: /net/aspose.svg.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Returns the next node in the set and advances the position of the iterator in the set. After a NodeIterator is created, the first call to nextNode() returns the first node in the set.

```csharp
public Node NextNode()
```

### Return Value

The next Node in the set being iterated over, or null if there are no more members in that set.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: Raised if this method is called after the detach method was invoked. |

### See Also

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
