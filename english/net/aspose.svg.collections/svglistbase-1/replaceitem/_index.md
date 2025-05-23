---
title: SVGListBase-1.ReplaceItem
second_title: Aspose.SVG for .NET API Reference
description: SVGListBase ReplaceItem method. Replaces an existing item in the list with a new item
type: docs
weight: 110
url: /net/aspose.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase<T>.ReplaceItem method

Replaces an existing item in the list with a new item.

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newItem | T | The item which is to be inserted into the list. |
| index | UInt64 | The index of the item which is to be replaced. The first item is number 0. |

### Return Value

The inserted item.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Raised when the list cannot be modified. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Raised if the index number is greater than or equal to numberOfItems. |

### See Also

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
