---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGListBase InsertItemBefore-methode. Voegt een nieuw item in de lijst in op de opgegeven positie. Het eerste item heeft nummer 0."
type: docs
weight: 90
url: /nl/net/aspose.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase<T>.InsertItemBefore method

Voegt een nieuw item in de lijst in op de opgegeven positie. Het eerste item heeft nummer 0.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newItem | T | Het item dat in de lijst moet worden ingevoegd. |
| index | UInt64 | De index van het item vóór welk het nieuwe item moet worden ingevoegd. Het eerste item heeft nummer 0. Als de index gelijk is aan 0, wordt het nieuwe item aan het begin van de lijst ingevoegd. Als de index groter dan of gelijk aan numberOfItems is, wordt het nieuwe item aan het einde van de lijst toegevoegd. |

### Retourwaarde

Het ingevoegde item.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Wordt opgegooid wanneer de lijst niet kan worden gewijzigd. |

### Zie ook

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
