---
title: SVGListBase-1.InsertItemBefore
second_title: Aspose.SVG for .NET API Reference
description: SVGListBase method. Inserts a new item into the list at the specified position. The first item is number 0
type: docs
weight: 90
url: /net/aspose.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Inserts a new item into the list at the specified position. The first item is number 0.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newItem | T | The item which is to be inserted into the list. |
| index | UInt64 | The index of the item before which the new item is to be inserted. The first item is number 0. If the index is equal to 0, then the new item is inserted at the front of the list. If the index is greater than or equal to numberOfItems, then the new item is appended to the end of the list. |

### Return Value

The inserted item.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Raised when the list cannot be modified. |

### See Also

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../svglistbase-1/)
* assembly [Aspose.SVG](../../../)
