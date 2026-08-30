---
title: "ITrueTypeFont-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Drawing.ITrueTypeFont-gränssnitt. Deklarerar metoder för att arbeta med TrueType-teckensnitt."
type: docs
weight: 3540
url: /sv/net/aspose.svg.drawing/itruetypefont/
---
## ITrueTypeFont interface

Deklarerar metoder för att arbeta med TrueType-teckensnitt.

```csharp
public interface ITrueTypeFont
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DataSize](../../aspose.svg.drawing/itruetypefont/datasize/) { get; } | Hämtar storleken på teckensnittsdata i byte. |
| [FamilyName](../../aspose.svg.drawing/itruetypefont/familyname/) { get; } | Hämtar namnet på teckensnittsfamiljen. |
| [FullFontName](../../aspose.svg.drawing/itruetypefont/fullfontname/) { get; } | Det fullständiga teckensnittsnamnet representeras vanligtvis som en kombination av familj- och underfamiljenamn. |
| [Style](../../aspose.svg.drawing/itruetypefont/style/) { get; } | Hämta teckensnittsstilen som kombinerar värdena från font-face-regeln och data från teckensnittet. |
| [SubFamilyName](../../aspose.svg.drawing/itruetypefont/subfamilyname/) { get; } | Underfamiljenamnet särskiljer teckensnittet i en grupp med samma familjenamn. Detta antas hantera stil (italic, oblique) och vikt (light, bold, black, etc.). Ett teckensnitt utan särskilda skillnader i vikt eller stil bör ha strängen "Regular". |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetAscent](../../aspose.svg.drawing/itruetypefont/getascent/)(*float*) | Hämtar teckensnittets ascent i punkter med den angivna teckensnittsstorleken. |
| [GetData](../../aspose.svg.drawing/itruetypefont/getdata/)() | Öppnar strömmen med teckensnittsdata. Anroparen ansvarar för att disponera strömmen. |
| [GetDescent](../../aspose.svg.drawing/itruetypefont/getdescent/)(*float*) | Hämtar teckensnittets descent i punkter med den angivna teckensnittsstorleken. |

### Se även

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
