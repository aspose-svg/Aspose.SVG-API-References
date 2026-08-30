---
title: "SVGListBase-1.ReplaceItem"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGListBase ReplaceItem-metoden. Ersätter ett befintligt objekt i listan med ett nytt objekt."
type: docs
weight: 110
url: /sv/net/aspose.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase<T>.ReplaceItem method

Ersätter ett befintligt objekt i listan med ett nytt objekt.

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newItem | T | Objektet som ska infogas i listan. |
| index | UInt64 | Indexet för objektet som ska ersättas. Det första objektet har nummer 0. |

### Returvärde

Det infogade objektet.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Utlöst när listan inte kan modifieras. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Utlöst om indexnumret är större än eller lika med numberOfItems. |

### Se även

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
