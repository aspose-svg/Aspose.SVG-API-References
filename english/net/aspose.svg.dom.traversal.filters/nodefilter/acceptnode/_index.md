---
title: NodeFilter.AcceptNode
second_title: Aspose.SVG for .NET API Reference
description: NodeFilter AcceptNode method. Test whether a specified node is visible in the logical view of a TreeWalker or NodeIterator. This function will be called by the implementation of TreeWalker and NodeIterator it is not normally called directly from user code. Though you could do so if you wanted to use the same filter to guide your own application logic
type: docs
weight: 10
url: /net/aspose.svg.dom.traversal.filters/nodefilter/acceptnode/
---
## NodeFilter.AcceptNode method

Test whether a specified node is visible in the logical view of a TreeWalker or NodeIterator. This function will be called by the implementation of TreeWalker and NodeIterator; it is not normally called directly from user code. (Though you could do so if you wanted to use the same filter to guide your own application logic.)

```csharp
public abstract short AcceptNode(Node n)
```

| Parameter | Type | Description |
| --- | --- | --- |
| n | Node | node to check to see if it passes the filter or not. |

### Return Value

a constant to determine whether the node is accepted, rejected, or skipped, as defined above.

### See Also

* class [Node](../../../aspose.svg.dom/node/)
* class [NodeFilter](../)
* namespace [Aspose.Svg.Dom.Traversal.Filters](../../../aspose.svg.dom.traversal.filters/)
* assembly [Aspose.SVG](../../../)
