---
title: "SVGListBase-1.Item"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGListBase Item-Eigenschaft. Gibt das Element an der Indexposition in der Liste zurück."
type: docs
weight: 10
url: /de/net/aspose.svg.collections/svglistbase-1/item/
---
## SVGListBase<T> indexer

Gibt das Element an der Index‑Position in der Liste zurück.

```csharp
public T this[ulong index] { get; set; }
```

| Parameter | Beschreibung |
| --- | --- |
| index | Index in der Liste. |

### Rückgabewert

Das gespeicherte Objekt an der Indexposition in der Liste.

### Property Value

Der Typ des in der Liste gespeicherten Elements.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Wird ausgelöst, wenn die Liste nicht geändert werden kann. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Wird ausgelöst, wenn die Indexnummer größer oder gleich numberOfItems ist. |

### Siehe auch

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
