---
title: XPathResultType Enum
second_title: Aspose.SVG for .NET API Reference
description: Aspose.Svg.Dom.XPath.XPathResultType enum. An unsigned short indicating what type of result this is. If a specific type is specified then the result will be returned as the corresponding type using XPath type conversions where required and possible
type: docs
weight: 3450
url: /net/aspose.svg.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

An unsigned short indicating what type of result this is. If a specific `type` is specified, then the result will be returned as the corresponding type, using XPath type conversions where required and possible.

```csharp
public enum XPathResultType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Any | `0` | This code does not represent a specific type. An evaluation of an XPath expression will never produce this type. If this type is requested, then the evaluation returns whatever type naturally results from evaluation of the expression. If the natural result is a node set when `Any` type was requested, then `UnorderedNodeIterator` is always the resulting type. Any other representation of a node set must be explicitly requested. |
| Number | `1` | The result is a number as defined by [XPath 1.0]. Document modification does not invalidate the number, but may mean that reevaluation would not yield the same number. |
| String | `2` | The result is a string as defined by [XPath 1.0]. Document modification does not invalidate the string, but may mean that the string no longer corresponds to the current document. |
| Boolean | `3` | The result is a boolean as defined by [XPath 1.0]. Document modification does not invalidate the boolean, but may mean that reevaluation would not yield the same boolean. |
| UnorderedNodeIterator | `4` | The result is a node set as defined by [XPath 1.0] that will be accessed iteratively, which may not produce nodes in a particular order. Document modification invalidates the iteration. This is the default type returned if the result is a node set and `Any` type is requested. |
| OrderedNodeIterator | `5` | The result is a node set as defined by [XPath 1.0] that will be accessed iteratively, which will produce document-ordered nodes. Document modification invalidates the iteration. |
| UnorderedNodeSnapshot | `6` | The result is a node set as defined by [XPath 1.0] that will be accessed as a snapshot list of nodes that may not be in a particular order. Document modification does not invalidate the snapshot but may mean that reevaluation would not yield the same snapshot and nodes in the snapshot may have been altered, moved, or removed from the document. |
| OrderedNodeSnapshot | `7` | The result is a node set as defined by [XPath 1.0] that will be accessed as a snapshot list of nodes that will be in original document order. Document modification does not invalidate the snapshot but may mean that reevaluation would not yield the same snapshot and nodes in the snapshot may have been altered, moved, or removed from the document. |
| AnyUnorderedNode | `8` | The result is a node set as defined by [XPath 1.0] and will be accessed as a single node, which may be `null` if the node set is empty. Document modification does not invalidate the node, but may mean that the result node no longer corresponds to the current document. This is a convenience that permits optimization since the implementation can stop once any node in the resulting set has been found. If there is more than one node in the actual result, the single node returned might not be the first in document order. |
| FirstOrderedNode | `9` | The result is a node set as defined by [XPath 1.0] and will be accessed as a single node, which may be `null` if the node set is empty. Document modification does not invalidate the node, but may mean that the result node no longer corresponds to the current document. This is a convenience that permits optimization since the implementation can stop once the first node in document order of the resulting set has been found. If there are more than one node in the actual result, the single node returned will be the first in document order. |

### See Also

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
