---
title: "SVGListBase-1.GetItem"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGListBase GetItem-Methode. Gibt das angegebene Element aus der Liste zurück."
type: docs
weight: 70
url: /de/net/aspose.svg.collections/svglistbase-1/getitem/
---
## SVGListBase<T>.GetItem method

Gibt das angegebene Element aus der Liste zurück.

```csharp
public T GetItem(ulong index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | UInt64 | Der Index des aus der Liste zurückzugebenden Elements. Das erste Element hat die Nummer 0. |

### Rückgabewert

Das ausgewählte Element.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Wird ausgelöst, wenn die Indexnummer größer oder gleich numberOfItems ist. |

### Siehe auch

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
