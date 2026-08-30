---
title: "SVGListBase-1.GetItem"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGListBase GetItem-metoden. Returnerar det angivna objektet från listan"
type: docs
weight: 70
url: /sv/net/aspose.svg.collections/svglistbase-1/getitem/
---
## SVGListBase<T>.GetItem method

Returnerar det angivna objektet från listan.

```csharp
public T GetItem(ulong index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | UInt64 | Indexet för objektet i listan som ska returneras. Det första objektet har nummer 0. |

### Returvärde

Det valda objektet.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Utlöst om indexnumret är större än eller lika med numberOfItems. |

### Se även

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
