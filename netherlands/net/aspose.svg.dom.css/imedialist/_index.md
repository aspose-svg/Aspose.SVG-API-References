---
title: "IMediaList interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Css.IMediaList interface. De MediaList-interface biedt de abstractie van een geordende verzameling media zonder te definiëren of te beperken hoe deze verzameling wordt geïmplementeerd. Een lege lijst is hetzelfde als een lijst die het medium all bevat."
type: docs
weight: 2730
url: /nl/net/aspose.svg.dom.css/imedialist/
---
## IMediaList interface

De MediaList interface biedt de abstractie van een geordende collectie van media, zonder te definiëren of te beperken hoe deze collectie wordt geïmplementeerd. Een lege lijst is hetzelfde als een lijst die het medium "all" bevat.

```csharp
public interface IMediaList : IEnumerable<string>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Item](../../aspose.svg.dom.css/imedialist/item/) { get; } | Retourneert het indexde element in de lijst. Als index groter dan of gelijk is aan het aantal media in de lijst, wordt null geretourneerd. De media-index. |
| [Length](../../aspose.svg.dom.css/imedialist/length/) { get; } | Het aantal media in de lijst. Het bereik van geldige media is 0 tot en met length-1. |
| [MediaText](../../aspose.svg.dom.css/imedialist/mediatext/) { get; } | De parseerbare tekstuele weergave van de mediaplijst. Dit is een door komma's gescheiden lijst van media. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AppendMedium](../../aspose.svg.dom.css/imedialist/appendmedium/)(*string*) | Voegt het medium newMedium toe aan het einde van de lijst. Als newMedium al wordt gebruikt, wordt het eerst verwijderd. |
| [DeleteMedium](../../aspose.svg.dom.css/imedialist/deletemedium/)(*string*) | Verwijdert het medium aangeduid door oldMedium uit de lijst. |

### Zie ook

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
