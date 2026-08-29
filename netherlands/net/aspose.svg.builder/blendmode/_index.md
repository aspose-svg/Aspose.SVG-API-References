---
title: "BlendMode Enum"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.BlendMode enum. Specificeert de mengmodi die beschikbaar zijn voor het combineren van afbeeldingen of elementen in SVG."
type: docs
weight: 80
url: /nl/net/aspose.svg.builder/blendmode/
---
## BlendMode enumeration

Specificeert de mengmodi die beschikbaar zijn voor het combineren van afbeeldingen of elementen in SVG.

```csharp
public enum BlendMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Normal | `0` | Toont de bronafbeelding zoals deze is, zonder enige menging. |
| Multiply | `1` | Vermenigvuldigt de kleuren van de bronafbeelding en de achtergrond. Het resultaat is een donkerder beeld. |
| Screen | `2` | Maakt de donkere delen van de bronafbeelding lichter en laat de lichte delen ongewijzigd. |
| Overlay | `3` | Combineert Multiply en Screen blend modes om het contrast te verbeteren. |
| Darken | `4` | Verdonkert de achtergrond op basis van de kleuren van de bronafbeelding. |
| Lighten | `5` | Verlicht de achtergrond op basis van de kleuren van de bronafbeelding. |
| ColorDodge | `6` | Verheldert de achtergrond om de bronafbeelding te weerspiegelen. |
| ColorBurn | `7` | Verdonkert de achtergrond om de bronafbeelding te weerspiegelen. |
| HardLight | `8` | Creëert een hard light-effect op basis van de helderheid van de bronafbeelding. |
| SoftLight | `9` | Creëert een soft light-effect op basis van de helderheid van de bronafbeelding. |
| Difference | `10` | Benadrukt de verschillen tussen de bronafbeelding en de achtergrond. |
| Exclusion | `11` | Creëert een effect vergelijkbaar met Difference, maar met een lager contrast. |
| Hue | `12` | Gebruikt de tint van de bronafbeelding gecombineerd met de luminantie en verzadiging van de achtergrond. |
| Saturation | `13` | Gebruikt de verzadiging van de bronafbeelding gecombineerd met de tint en luminantie van de achtergrond. |
| Color | `14` | Gebruikt de tint en verzadiging van de bronafbeelding gecombineerd met de luminantie van de achtergrond. |
| Luminosity | `15` | Gebruikt de luminantie van de bronafbeelding gecombineerd met de tint en verzadiging van de achtergrond. |

## Opmerkingen

Blendmodi in SVG worden gebruikt om te bepalen hoe twee lagen in elkaar worden gemengd. Deze enum biedt een verscheidenheid aan opties die regelen hoe de kleuren van de gemengde lagen zich mengen en verschillende visuele effecten produceren.

### Zie ook

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
