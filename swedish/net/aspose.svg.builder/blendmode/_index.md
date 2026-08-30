---
title: "BlendMode enum"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.BlendMode enum. Anger de blandningslägen som finns tillgängliga för att kombinera bilder eller element i SVG"
type: docs
weight: 80
url: /sv/net/aspose.svg.builder/blendmode/
---
## BlendMode enumeration

Anger blandningslägena som är tillgängliga för att kombinera bilder eller element i SVG.

```csharp
public enum BlendMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Normal | `0` | Visar källbilden som den är, utan någon blandning. |
| Multiply | `1` | Multiplicerar färgerna i källbilden och bakgrunden. Resultatet blir en mörkare bild. |
| Screen | `2` | Gör de mörka delarna av källbilden ljusare och de ljusa delarna oförändrade. |
| Overlay | `3` | Kombinerar Multiply- och Screen-blandningslägen för att förbättra kontrasten. |
| Darken | `4` | Mörkar bakgrunden baserat på källbildens färger. |
| Lighten | `5` | Ljusar upp bakgrunden baserat på källbildens färger. |
| ColorDodge | `6` | Ljusar upp bakgrunden för att återspegla källbilden. |
| ColorBurn | `7` | Mörkar ner bakgrunden för att återspegla källbilden. |
| HardLight | `8` | Skapar en hård ljuseffekt baserad på källbildens ljusstyrka. |
| SoftLight | `9` | Skapar en mjuk ljuseffekt baserad på källbildens ljusstyrka. |
| Difference | `10` | Markerar skillnaderna mellan källbilden och bakgrunden. |
| Exclusion | `11` | Skapar en effekt liknande Difference, men med lägre kontrast. |
| Hue | `12` | Använder nyansen från källbilden kombinerad med luminansen och mättnaden i bakgrunden. |
| Saturation | `13` | Använder mättnaden från källbilden kombinerad med nyansen och luminansen i bakgrunden. |
| Color | `14` | Använder nyansen och mättnaden från källbilden kombinerad med luminansen i bakgrunden. |
| Luminosity | `15` | Använder luminansen från källbilden kombinerad med nyansen och mättnaden i bakgrunden. |

## Anmärkningar

Blandningslägen i SVG används för att bestämma hur två lager blandas med varandra. Denna enum erbjuder en mängd alternativ som styr hur färgerna i de blandade lagren blandas och skapar olika visuella effekter.

### Se även

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
