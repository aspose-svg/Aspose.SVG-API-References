---
title: "SVGListBase-1.GetItem"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGListBase GetItem-methode. Retourneert het opgegeven item uit de lijst."
type: docs
weight: 70
url: /nl/net/aspose.svg.collections/svglistbase-1/getitem/
---
## SVGListBase<T>.GetItem method

Retourneert het opgegeven item uit de lijst.

```csharp
public T GetItem(ulong index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | UInt64 | De index van het item uit de lijst dat moet worden geretourneerd. Het eerste item heeft nummer 0. |

### Retourwaarde

Het geselecteerde item.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Wordt opgegooid als het indexnummer groter dan of gelijk aan numberOfItems is. |

### Zie ook

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
