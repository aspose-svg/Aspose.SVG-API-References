---
title: "Color-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Drawing.Color-klass. Color-klassen låter dig ange färger som Red-Green-Blue RGB-värden, Hue-Saturation-Luminosity HSL-värden, Hue-Saturation-Value HSV-värden, Hue-Whiteness-Blackness HWB-värden, lightness-A-B LAB-värden, Luminance-Chroma-Hue LCH-värden, Cyan-Magenta-Yellow-Key CMYK-värden, Natural colors NCOL-värden eller med ett färgnamn. En Alpha-kanal är också tillgänglig för att ange transparens."
type: docs
weight: 3390
url: /sv/net/aspose.svg.drawing/color/
---
## Color class

Color-klassen låter dig specificera färger som Red-Green-Blue (RGB)-värden, Hue-Saturation-Luminosity (HSL)-värden, Hue-Saturation-Value (HSV)-värden, Hue-Whiteness-Blackness (HWB)-värden, lightness-A-B (LAB)-värden, Luminance-Chroma-Hue (LCH)-värden, Cyan-Magenta-Yellow-Key (CMYK)-värden, Natural colors (NCOL)-värden, eller med ett färgnamn. En Alpha-kanal är också tillgänglig för att ange transparens.

```csharp
public class Color
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Color](color/#constructor)() | Initierar en ny instans av `Color`-klassen. Som standard är färgen svart. |
| [Color](color/#constructor_1)(*byte, byte, byte*) | Initierar en ny instans av `Color`-klassen. Alla färgkomponenter måste ligga i intervallet 0‑255. |
| [Color](color/#constructor_5)(*float, float, float*) | Initierar en ny instans av `Color`-klassen. Alla färgkomponenter måste ligga i intervallet 0‑1. |
| [Color](color/#constructor_3)(*int, int, int*) | Initierar en ny instans av `Color`-klassen. Alla färgkomponenter måste ligga i intervallet 0‑255. |
| [Color](color/#constructor_2)(*byte, byte, byte, byte*) | Initierar en ny instans av `Color`-klassen. Alla färgkomponenter måste ligga i intervallet 0‑255. |
| [Color](color/#constructor_6)(*float, float, float, float*) | Initierar en ny instans av `Color`-klassen. Alla färgkomponenter måste ligga i intervallet 0‑1. |
| [Color](color/#constructor_4)(*int, int, int, int*) | Initierar en ny instans av `Color`-klassen. Alla färgkomponenter måste ligga i intervallet 0‑255. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Alpha](../../aspose.svg.drawing/color/alpha/) { get; } | Representerar alfakomponenten i färgen. |
| [Blue](../../aspose.svg.drawing/color/blue/) { get; } | Representerar den blå komponenten i färgen. |
| [Green](../../aspose.svg.drawing/color/green/) { get; } | Representerar den gröna komponenten i färgen. |
| [Red](../../aspose.svg.drawing/color/red/) { get; } | Representerar den röda komponenten i färgen |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromCmyk](../../aspose.svg.drawing/color/fromcmyk/)(*float, float, float, float*) | Returnerar en ny Color med de begärda cyan-, magenta-, gul- och key (svart)-värdena. |
| static [FromCmyka](../../aspose.svg.drawing/color/fromcmyka/)(*float, float, float, float, float*) | Returnerar en ny Color med de begärda cyan, magenta, yellow, key (black), alpha‑värdena. |
| static [FromGray](../../aspose.svg.drawing/color/fromgray/)(*float*) | Returnerar en ny Color med det begärda gråvärdet. |
| static [FromHsl](../../aspose.svg.drawing/color/fromhsl/)(*float, float, float*) | Returnerar en ny Color med de begärda hue, saturation, saturation‑värdena. |
| static [FromHsla](../../aspose.svg.drawing/color/fromhsla/)(*float, float, float, float*) | Returnerar en ny Color med de begärda hue, saturation, saturation, alpha‑värdena. |
| static [FromHsv](../../aspose.svg.drawing/color/fromhsv/)(*float, float, float*) | Returnerar en ny Color med de begärda hue, saturation, value‑värdena. |
| static [FromHsva](../../aspose.svg.drawing/color/fromhsva/)(*float, float, float, float*) | Returnerar en ny Color med de begärda hue, saturation, value, alpha‑värdena. |
| static [FromHwb](../../aspose.svg.drawing/color/fromhwb/)(*float, float, float*) | Returnerar en ny Color med de begärda hue, whiteness, blackness‑värdena. |
| static [FromHwba](../../aspose.svg.drawing/color/fromhwba/)(*float, float, float, float*) | Returnerar en ny Color med de begärda hue, whiteness, blackness‑värdena. |
| static [FromInt](../../aspose.svg.drawing/color/fromint/)(*int*) | Returnerar en ny Color med det begärda ARGB‑värdet. |
| static [FromLab](../../aspose.svg.drawing/color/fromlab/)(*float, float, float*) | Returnerar en ny Color med de begärda lightness, A, B‑värdena. |
| static [FromLaba](../../aspose.svg.drawing/color/fromlaba/)(*float, float, float, float*) | Returnerar en ny Color med de begärda lightness, A, B, alpha‑värdena. |
| static [FromLch](../../aspose.svg.drawing/color/fromlch/)(*float, float, float*) | Returnerar en ny Color med de begärda luminance, chroma, hue‑värdena. |
| static [FromLcha](../../aspose.svg.drawing/color/fromlcha/)(*float, float, float, float*) | Returnerar en ny Color med de begärda luminance, chroma, hue, alpha‑värdena. |
| static [FromOklab](../../aspose.svg.drawing/color/fromoklab/)(*float, float, float*) | Returnerar en ny Color med de begärda lightness, A, B‑värdena för OKLAB‑modellen. |
| static [FromOklaba](../../aspose.svg.drawing/color/fromoklaba/)(*float, float, float, float*) | Returnerar en ny Color med de begärda lightness, A, B, alpha‑värdena för OKLAB‑modellen. |
| static [FromOklch](../../aspose.svg.drawing/color/fromoklch/)(*float, float, float*) | Returnerar en ny Color med de begärda luminance, chroma, hue‑värdena för OKLAB‑modellen. |
| static [FromOklcha](../../aspose.svg.drawing/color/fromoklcha/)(*float, float, float, float*) | Returnerar en ny Color med de begärda luminance, chroma, hue, alpha‑värdena för OKLAB‑modellen. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb)(*byte, byte, byte*) | Returnerar en ny Color med de begärda ged, green, blue‑värdena. Alla färgkomponenter måste ligga i intervallet 0‑255. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb_2)(*float, float, float*) | Returnerar en ny Color med de begärda ged, green, blue‑värdena. Alla färgkomponenter måste ligga i intervallet 0‑1. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb_1)(*int, int, int*) | Returnerar en ny Color med de begärda ged, green, blue‑värdena. Alla färgkomponenter måste ligga i intervallet 0‑255. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba)(*byte, byte, byte, byte*) | Returnerar en ny Color med de begärda ged, green, blue, alpha‑värdena. Alla färgkomponenter måste ligga i intervallet 0‑255. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba_2)(*float, float, float, float*) | Returnerar en ny Color med de begärda ged, green, blue, alpha‑värdena. Alla färgkomponenter måste ligga i intervallet 0‑1. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba_1)(*int, int, int, int*) | Returnerar en ny Color med de begärda ged, green, blue, alpha‑värdena. Alla färgkomponenter måste ligga i intervallet 0‑255. |
| static [FromString](../../aspose.svg.drawing/color/fromstring/)(*string*) | Analyserar en sträng som innehåller CSS‑färgen och returnerar en ny Color. |
| static [FromUint](../../aspose.svg.drawing/color/fromuint/)(*uint*) | Returnerar en ny Color med det begärda ARGB‑värdet. |
| [AddLuminosity](../../aspose.svg.drawing/color/addluminosity/)(*float*) | Skapar en kopia av Color med summan av dess luminositet och delta‑värdet. |
| [Convert](../../aspose.svg.drawing/color/convert/)(*[ColorModel](../colormodel/)*) | Returnerar färgkomponenter i formatet för den angivna färgmodellen. |
| override [Equals](../../aspose.svg.drawing/color/equals/)(*object*) | Bestämmer om den angivna `Color` är lika med detta objekt. |
| [GetComplementary](../../aspose.svg.drawing/color/getcomplementary/)() | Returnerar en ny färg som ligger på motsatt sida av färghjulet jämfört med originalet. |
| override [GetHashCode](../../aspose.svg.drawing/color/gethashcode/)() | Returnerar en hashkod. |
| [GetHue](../../aspose.svg.drawing/color/gethue/)() | Returnerar en nyans av färgen. |
| [GetLuminosity](../../aspose.svg.drawing/color/getluminosity/)() | Returnerar en luminans av färgen. |
| [GetSaturation](../../aspose.svg.drawing/color/getsaturation/)() | Returnerar en mättnad av färgen. |
| [ToInt](../../aspose.svg.drawing/color/toint/)() | Kodar färgens ARGB-komponenter till int. |
| [ToName](../../aspose.svg.drawing/color/toname/)() | Returnerar färgens namn om den matchar en färg i listan över CSS-namnade färger, eller en tom sträng. |
| [ToNaturalColorString](../../aspose.svg.drawing/color/tonaturalcolorstring/)(*int*) | Returnerar en Natural colors (NCol) specificerad färg med en färg bokstav och ett nummer för att ange avståndet (i procent) från färgen. |
| [ToRgbaHexString](../../aspose.svg.drawing/color/torgbahexstring/)() | Returnerar en hexadecimal färg som specificeras med: #RRGGBBAA. |
| [ToRgbaString](../../aspose.svg.drawing/color/torgbastring/)() | Returnerar en sträng som innehåller RGBA-färgen specificerad av: rgba(R, G, B, A). |
| [ToRgbHexString](../../aspose.svg.drawing/color/torgbhexstring/)() | Returnerar en hexadecimal färg som specificeras med: #RRGGBB. |
| [ToRgbString](../../aspose.svg.drawing/color/torgbstring/)() | Returnerar en sträng som innehåller RGB-färgen specificerad av: rgb(R, G, B). |
| override [ToString](../../aspose.svg.drawing/color/tostring/)() | Returnerar en sträng som består av RGBA-komponentvärdena. |
| [ToUint](../../aspose.svg.drawing/color/touint/)() | Kodar färgens ARGB-komponenter till unsigned int. |
| [WithAlpha](../../aspose.svg.drawing/color/withalpha/)(*float*) | Skapar en kopia av färgen med specificerad alfa-komponent. |
| [WithHue](../../aspose.svg.drawing/color/withhue/)(*float*) | Skapar en kopia av färgen med specificerad nyans. |
| [WithLuminosity](../../aspose.svg.drawing/color/withluminosity/)(*float*) | Skapar en kopia av färgen med specificerad luminans. |
| [WithSaturation](../../aspose.svg.drawing/color/withsaturation/)(*float*) | Skapar en kopia av färgen med specificerad mättnad. |

### Se även

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
