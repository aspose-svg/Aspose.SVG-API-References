---
title: SVGListBase-1.Item
second_title: Aspose.SVG for .NET API Reference
description: SVGListBase property. Returns the indexth item in the list
type: docs
weight: 10
url: /net/aspose.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Returns the indexth item in the list.

```csharp
public T this[ulong index] { get; set; }
```

| Parameter | Description |
| --- | --- |
| index | Index in the list. |

### Return Value

The stored object at the indexth position in the list.

### Property Value

The type of item stored in list.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Raised when the list cannot be modified. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Raised if the index number is greater than or equal to numberOfItems. |

### See Also

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../svglistbase-1/)
* assembly [Aspose.SVG](../../../)
