---
title: SVGListBase-1.GetItem
second_title: Aspose.SVG for .NET API Reference
description: SVGListBase GetItem method. Returns the specified item from the list
type: docs
weight: 70
url: /net/aspose.svg.collections/svglistbase-1/getitem/
---
## SVGListBase<T>.GetItem method

Returns the specified item from the list.

```csharp
public T GetItem(ulong index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | UInt64 | The index of the item from the list which is to be returned. The first item is number 0. |

### Return Value

The selected item.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Raised if the index number is greater than or equal to numberOfItems. |

### See Also

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
