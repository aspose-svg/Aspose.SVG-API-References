---
title: "SVGListBase-1.Item"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGListBase Item-egenskap. Returnerar objektet på det angivna indexet i listan."
type: docs
weight: 10
url: /sv/net/aspose.svg.collections/svglistbase-1/item/
---
## SVGListBase<T> indexer

Returnerar det index‑te objektet i listan.

```csharp
public T this[ulong index] { get; set; }
```

| Parameter | Beskrivning |
| --- | --- |
| index | Index i listan. |

### Returvärde

Det lagrade objektet på den angivna positionen i listan.

### Property Value

Typen av objekt som lagras i listan.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Utlöst när listan inte kan modifieras. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Utlöst om indexnumret är större än eller lika med numberOfItems. |

### Se även

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
