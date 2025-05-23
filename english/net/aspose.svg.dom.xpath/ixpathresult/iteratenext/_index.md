---
title: IXPathResult.IterateNext
second_title: Aspose.SVG for .NET API Reference
description: IXPathResult IterateNext method. Iterates and returns the next node from the node set or null if there are no more nodes
type: docs
weight: 80
url: /net/aspose.svg.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

Iterates and returns the next node from the node set or `null` if there are no more nodes.

```csharp
public Node IterateNext()
```

### Return Value

Returns the next node.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: raised if `resultType` is not `UnorderedNodeIterator` type or `OrderedNodeIterator` type. |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: The document has been mutated since the result was returned. |

### See Also

* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
