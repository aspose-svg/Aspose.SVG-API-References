---
title: "SVGListBaseT Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Collections.SVGListBase1T Klasse. Dieses Interface definiert eine Basissammlung aller SVG-Listen"
type: docs
weight: 2040
url: /de/net/aspose.svg.collections/svglistbase-1/
---
## SVGListBase<T> class

Dieses Interface definiert eine Basisliste aller SVG-Listen.

```csharp
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| Parameter | Beschreibung |
| --- | --- |
| T | Typ des in der Liste gespeicherten Elements. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Item](../../aspose.svg.collections/svglistbase-1/item/) { get; set; } | Gibt das Element an der Index‑Position in der Liste zurück. |
| [Length](../../aspose.svg.collections/svglistbase-1/length/) { get; } | Die Anzahl der Elemente in der Liste. |
| [NumberOfItems](../../aspose.svg.collections/svglistbase-1/numberofitems/) { get; } | Die Anzahl der Elemente in der Liste. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AppendItem](../../aspose.svg.collections/svglistbase-1/appenditem/)(*T*) | Fügt ein neues Element am Ende der Liste ein. |
| [Clear](../../aspose.svg.collections/svglistbase-1/clear/)() | Löscht alle vorhandenen aktuellen Elemente aus der Liste, sodass das Ergebnis eine leere Liste ist. |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Gibt nicht verwaltete und – optional – verwaltete Ressourcen frei. |
| [GetEnumerator](../../aspose.svg.collections/svglistbase-1/getenumerator/)() | Liefert den Enumerator. |
| [GetItem](../../aspose.svg.collections/svglistbase-1/getitem/)(*ulong*) | Gibt das angegebene Element aus der Liste zurück. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [Initialize](../../aspose.svg.collections/svglistbase-1/initialize/)(*T*) | Löscht alle vorhandenen aktuellen Elemente aus der Liste und initialisiert die Liste neu, um das einzelne durch den Parameter angegebene Element zu halten. |
| [InsertItemBefore](../../aspose.svg.collections/svglistbase-1/insertitembefore/)(*T, ulong*) | Fügt ein neues Element an der angegebenen Position in die Liste ein. Das erste Element hat die Nummer 0. |
| [RemoveItem](../../aspose.svg.collections/svglistbase-1/removeitem/)(*ulong*) | Entfernt ein vorhandenes Element aus der Liste. |
| [ReplaceItem](../../aspose.svg.collections/svglistbase-1/replaceitem/)(*T, ulong*) | Ersetzt ein vorhandenes Element in der Liste durch ein neues Element. |

### Siehe auch

* class [SVGValueType](../../aspose.svg.datatypes/svgvaluetype/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
