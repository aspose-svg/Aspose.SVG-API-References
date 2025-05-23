---
title: SVGListBase-1.RemoveItem
second_title: Aspose.SVG for .NET API Reference
description: SVGListBase RemoveItem method. Removes an existing item from the list
type: docs
weight: 100
url: /net/aspose.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase<T>.RemoveItem method

Removes an existing item from the list.

```csharp
public T RemoveItem(ulong index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | UInt64 | The index of the item which is to be removed. The first item is number 0. |

### Return Value

The removed item.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Raised when the list cannot be modified. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Raised if the index number is greater than or equal to numberOfItems. |

### See Also

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
