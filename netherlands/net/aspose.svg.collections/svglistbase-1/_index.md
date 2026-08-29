---
title: "SVGListBaseT Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Collections.SVGListBase1T class. Deze interface definieert een basislijst van alle SVG‑lijsten"
type: docs
weight: 2040
url: /nl/net/aspose.svg.collections/svglistbase-1/
---
## SVGListBase<T> class

Deze interface definieert een basislijst van alle SVG‑lijsten.

```csharp
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| Parameter | Beschrijving |
| --- | --- |
| T | Type van item opgeslagen in de lijst. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Item](../../aspose.svg.collections/svglistbase-1/item/) { get; set; } | Retourneert het index‑de item in de lijst. |
| [Length](../../aspose.svg.collections/svglistbase-1/length/) { get; } | Het aantal items in de lijst. |
| [NumberOfItems](../../aspose.svg.collections/svglistbase-1/numberofitems/) { get; } | Het aantal items in de lijst. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AppendItem](../../aspose.svg.collections/svglistbase-1/appenditem/)(*T*) | Voegt een nieuw item toe aan het einde van de lijst. |
| [Clear](../../aspose.svg.collections/svglistbase-1/clear/)() | Verwijdert alle bestaande huidige items uit de lijst, waardoor de lijst leeg wordt. |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Vrijgeeft niet‑beheerde en - optioneel - beheerde bronnen. |
| [GetEnumerator](../../aspose.svg.collections/svglistbase-1/getenumerator/)() | Verkrijgt de enumerator. |
| [GetItem](../../aspose.svg.collections/svglistbase-1/getitem/)(*ulong*) | Retourneert het opgegeven item uit de lijst. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [Initialize](../../aspose.svg.collections/svglistbase-1/initialize/)(*T*) | Verwijdert alle bestaande huidige items uit de lijst en initialiseert de lijst opnieuw om het enkele item dat door de parameter is opgegeven te bevatten. |
| [InsertItemBefore](../../aspose.svg.collections/svglistbase-1/insertitembefore/)(*T, ulong*) | Voegt een nieuw item in de lijst in op de opgegeven positie. Het eerste item heeft nummer 0. |
| [RemoveItem](../../aspose.svg.collections/svglistbase-1/removeitem/)(*ulong*) | Verwijdert een bestaand item uit de lijst. |
| [ReplaceItem](../../aspose.svg.collections/svglistbase-1/replaceitem/)(*T, ulong*) | Vervangt een bestaand item in de lijst door een nieuw item. |

### Zie ook

* class [SVGValueType](../../aspose.svg.datatypes/svgvaluetype/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
