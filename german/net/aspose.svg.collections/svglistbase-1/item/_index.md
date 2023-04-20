---
title: SVGListBase1.Item
second_title: Aspose.SVG für .NET-API-Referenz
description: SVGListBase eigendom. Gibt das indexierte Element in der Liste zurück.
type: docs
weight: 10
url: /de/net/aspose.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Gibt das indexierte Element in der Liste zurück.

```csharp
public T this[ulong index] { get; set; }
```

| Parameter | Beschreibung |
| --- | --- |
| index | Index in der Liste. |

### Rückgabewert

Das gespeicherte Objekt an der Indexposition in der Liste.

### Eigentumswert

Der in der Liste gespeicherte Elementtyp.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Wird ausgelöst, wenn die Liste nicht geändert werden kann. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code[`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Wird ausgelöst, wenn die Indexnummer größer oder gleich numberOfItems ist. |

### Siehe auch

* class [SVGListBase&lt;T&gt;](../)
* namensraum [Aspose.Svg.Collections](../../svglistbase-1/)
* Montage [Aspose.SVG](../../../)


