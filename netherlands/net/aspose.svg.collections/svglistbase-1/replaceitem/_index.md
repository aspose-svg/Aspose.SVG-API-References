---
title: "SVGListBase-1.ReplaceItem"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGListBase ReplaceItem-methode. Vervangt een bestaand item in de lijst door een nieuw item"
type: docs
weight: 110
url: /nl/net/aspose.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase<T>.ReplaceItem method

Vervangt een bestaand item in de lijst door een nieuw item.

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newItem | T | Het item dat in de lijst moet worden ingevoegd. |
| index | UInt64 | De index van het item dat moet worden vervangen. Het eerste item heeft nummer 0. |

### Retourwaarde

Het ingevoegde item.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Wordt opgegooid wanneer de lijst niet kan worden gewijzigd. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Wordt opgegooid als het indexnummer groter dan of gelijk aan numberOfItems is. |

### Zie ook

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
