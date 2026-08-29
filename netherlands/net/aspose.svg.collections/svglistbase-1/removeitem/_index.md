---
title: "SVGListBase-1.RemoveItem"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGListBase RemoveItem-methode. Verwijdert een bestaand item uit de lijst."
type: docs
weight: 100
url: /nl/net/aspose.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase<T>.RemoveItem method

Verwijdert een bestaand item uit de lijst.

```csharp
public T RemoveItem(ulong index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | UInt64 | De index van het item dat moet worden verwijderd. Het eerste item heeft nummer 0. |

### Retourwaarde

Het verwijderde item.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Wordt opgegooid wanneer de lijst niet kan worden gewijzigd. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Wordt opgegooid als het indexnummer groter dan of gelijk aan numberOfItems is. |

### Zie ook

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
