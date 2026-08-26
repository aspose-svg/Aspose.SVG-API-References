---
title: "SVGListBase-1.RemoveItem"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGListBase RemoveItem-Methode. Entfernt ein vorhandenes Element aus der Liste."
type: docs
weight: 100
url: /de/net/aspose.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase<T>.RemoveItem method

Entfernt ein vorhandenes Element aus der Liste.

```csharp
public T RemoveItem(ulong index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | UInt64 | Der Index des zu entfernenden Elements. Das erste Element hat die Nummer 0. |

### Rückgabewert

Das entfernte Element.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Wird ausgelöst, wenn die Liste nicht geändert werden kann. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Wird ausgelöst, wenn die Indexnummer größer oder gleich numberOfItems ist. |

### Siehe auch

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
