---
title: "SVGListBase-1.Item"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGListBase Item-eigenschap. Retourneert het item op de opgegeven index in de lijst."
type: docs
weight: 10
url: /nl/net/aspose.svg.collections/svglistbase-1/item/
---
## SVGListBase<T> indexer

Retourneert het index‑de item in de lijst.

```csharp
public T this[ulong index] { get; set; }
```

| Parameter | Beschrijving |
| --- | --- |
| index | Index in de lijst. |

### Retourwaarde

Het opgeslagen object op de opgegeven indexpositie in de lijst.

### Property Value

Het type item dat in de lijst is opgeslagen.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Wordt opgegooid wanneer de lijst niet kan worden gewijzigd. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Wordt opgegooid als het indexnummer groter dan of gelijk aan numberOfItems is. |

### Zie ook

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
