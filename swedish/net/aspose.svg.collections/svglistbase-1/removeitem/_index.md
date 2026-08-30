---
title: "SVGListBase-1.RemoveItem"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGListBase RemoveItem-metoden. Tar bort ett befintligt objekt från listan"
type: docs
weight: 100
url: /sv/net/aspose.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase<T>.RemoveItem method

Tar bort ett befintligt objekt från listan.

```csharp
public T RemoveItem(ulong index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | UInt64 | Indexet för objektet som ska tas bort. Det första objektet har nummer 0. |

### Returvärde

Det borttagna objektet.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Utlöst när listan inte kan modifieras. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Utlöst om indexnumret är större än eller lika med numberOfItems. |

### Se även

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
