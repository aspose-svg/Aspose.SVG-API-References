---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGListBase InsertItemBefore-metod. Infogar ett nytt objekt i listan på den angivna positionen. Det första objektet har nummer 0"
type: docs
weight: 90
url: /sv/net/aspose.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase<T>.InsertItemBefore method

Infogar ett nytt objekt i listan på den angivna positionen. Det första objektet har nummer 0.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newItem | T | Objektet som ska infogas i listan. |
| index | UInt64 | Indexet för objektet före vilket det nya objektet ska infogas. Det första objektet har nummer 0. Om indexet är lika med 0 infogas det nya objektet i början av listan. Om indexet är större än eller lika med numberOfItems infogas det nya objektet i slutet av listan. |

### Returvärde

Det infogade objektet.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Utlöst när listan inte kan modifieras. |

### Se även

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
