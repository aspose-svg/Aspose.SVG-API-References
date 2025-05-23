---
title: SVGListBase-1.Initialize
second_title: Aspose.SVG for .NET API Reference
description: SVGListBase Initialize method. Clears all existing current items from the list and re-initializes the list to hold the single item specified by the parameter
type: docs
weight: 80
url: /net/aspose.svg.collections/svglistbase-1/initialize/
---
## SVGListBase<T>.Initialize method

Clears all existing current items from the list and re-initializes the list to hold the single item specified by the parameter.

```csharp
public T Initialize(T newItem)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newItem | T | The item which should become the only member of the list. |

### Return Value

The item being inserted into the list.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Raised when the list cannot be modified. |

### See Also

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
