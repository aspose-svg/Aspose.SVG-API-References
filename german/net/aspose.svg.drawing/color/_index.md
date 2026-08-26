---
title: "Color Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Drawing.Color Klasse. Die Color Klasse ermöglicht es Ihnen, Farben als Red-Green-Blue RGB-Werte, Hue-Saturation-Luminosity HSL-Werte, Hue-Saturation-Value HSV-Werte, Hue-Whiteness-Blackness HWB-Werte, Lightness-A-B LAB-Werte, Luminance-Chroma-Hue LCH-Werte, Cyan-Magenta-Yellow-Key CMYK-Werte, Natural colors NCOL-Werte oder mit einem Farbnamen anzugeben. Ein Alpha-Kanal ist ebenfalls verfügbar, um Transparenz anzuzeigen."
type: docs
weight: 3390
url: /de/net/aspose.svg.drawing/color/
---
## Color class

Die Color‑Klasse ermöglicht es, Farben als Rot‑Grün‑Blau (RGB)-Werte, Farbton‑Sättigung‑Luminanz (HSL)-Werte, Farbton‑Sättigung‑Wert (HSV)-Werte, Farbton‑Weiß‑Schwarz (HWB)-Werte, Lightness‑A‑B (LAB)-Werte, Luminanz‑Chroma‑Farbton (LCH)-Werte, Cyan‑Magenta‑Yellow‑Key (CMYK)-Werte, Natürliche Farben (NCOL)-Werte oder über einen Farbnamen anzugeben. Ein Alpha‑Kanal ist ebenfalls verfügbar, um Transparenz anzugeben.

```csharp
public class Color
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Color](color/#constructor)() | Initialisiert eine neue Instanz der `Color` Klasse. Standardmäßig ist die Farbe schwarz. |
| [Color](color/#constructor_1)(*byte, byte, byte*) | Initialisiert eine neue Instanz der `Color` Klasse. Alle Farbkomponenten müssen im Bereich 0‑255 liegen. |
| [Color](color/#constructor_5)(*float, float, float*) | Initialisiert eine neue Instanz der `Color` Klasse. Alle Farbkomponenten müssen im Bereich 0‑1 liegen. |
| [Color](color/#constructor_3)(*int, int, int*) | Initialisiert eine neue Instanz der `Color` Klasse. Alle Farbkomponenten müssen im Bereich 0‑255 liegen. |
| [Color](color/#constructor_2)(*byte, byte, byte, byte*) | Initialisiert eine neue Instanz der `Color` Klasse. Alle Farbkomponenten müssen im Bereich 0‑255 liegen. |
| [Color](color/#constructor_6)(*float, float, float, float*) | Initialisiert eine neue Instanz der `Color` Klasse. Alle Farbkomponenten müssen im Bereich 0‑1 liegen. |
| [Color](color/#constructor_4)(*int, int, int, int*) | Initialisiert eine neue Instanz der `Color` Klasse. Alle Farbkomponenten müssen im Bereich 0‑255 liegen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Alpha](../../aspose.svg.drawing/color/alpha/) { get; } | Stellt die Alpha-Komponente der Farbe dar. |
| [Blue](../../aspose.svg.drawing/color/blue/) { get; } | Stellt die Blau-Komponente der Farbe dar. |
| [Green](../../aspose.svg.drawing/color/green/) { get; } | Stellt die Grün-Komponente der Farbe dar. |
| [Red](../../aspose.svg.drawing/color/red/) { get; } | Stellt die Rot-Komponente der Farbe dar |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromCmyk](../../aspose.svg.drawing/color/fromcmyk/)(*float, float, float, float*) | Gibt ein neues Color mit den gewünschten Cyan-, Magenta-, Yellow- und Key (Schwarz)-Werten zurück. |
| static [FromCmyka](../../aspose.svg.drawing/color/fromcmyka/)(*float, float, float, float, float*) | Gibt ein neues Color mit den gewünschten Cyan-, Magenta-, Yellow-, Key (Schwarz)- und Alpha-Werten zurück. |
| static [FromGray](../../aspose.svg.drawing/color/fromgray/)(*float*) | Gibt eine neue Color mit dem gewünschten Grauwert zurück. |
| static [FromHsl](../../aspose.svg.drawing/color/fromhsl/)(*float, float, float*) | Gibt eine neue Color mit den gewünschten Farbton-, Sättigungs- und Sättigungswerten zurück. |
| static [FromHsla](../../aspose.svg.drawing/color/fromhsla/)(*float, float, float, float*) | Gibt eine neue Color mit den gewünschten Farbton-, Sättigungs-, Sättigungs- und Alphawerten zurück. |
| static [FromHsv](../../aspose.svg.drawing/color/fromhsv/)(*float, float, float*) | Gibt eine neue Color mit dem gewünschten Farbton-, Sättigungs- und Wert zurück. |
| static [FromHsva](../../aspose.svg.drawing/color/fromhsva/)(*float, float, float, float*) | Gibt eine neue Color mit dem gewünschten Farbton-, Sättigungs-, Wert- und Alphawert zurück. |
| static [FromHwb](../../aspose.svg.drawing/color/fromhwb/)(*float, float, float*) | Gibt eine neue Color mit den gewünschten Farbton-, Weißheits- und Schwarzheitswerten zurück. |
| static [FromHwba](../../aspose.svg.drawing/color/fromhwba/)(*float, float, float, float*) | Gibt eine neue Color mit den gewünschten Farbton-, Weißheits- und Schwarzheitswerten zurück. |
| static [FromInt](../../aspose.svg.drawing/color/fromint/)(*int*) | Gibt eine neue Color mit dem gewünschten ARGB-Wert zurück. |
| static [FromLab](../../aspose.svg.drawing/color/fromlab/)(*float, float, float*) | Gibt eine neue Color mit den gewünschten Helligkeits-, A- und B-Werten zurück. |
| static [FromLaba](../../aspose.svg.drawing/color/fromlaba/)(*float, float, float, float*) | Gibt eine neue Color mit den gewünschten Helligkeits-, A-, B- und Alphawerten zurück. |
| static [FromLch](../../aspose.svg.drawing/color/fromlch/)(*float, float, float*) | Gibt eine neue Color mit den gewünschten Leuchtkraft-, Chroma- und Farbtonwerten zurück. |
| static [FromLcha](../../aspose.svg.drawing/color/fromlcha/)(*float, float, float, float*) | Gibt eine neue Color mit den gewünschten Leuchtkraft-, Chroma-, Farbton- und Alphawerten zurück. |
| static [FromOklab](../../aspose.svg.drawing/color/fromoklab/)(*float, float, float*) | Gibt eine neue Color mit den gewünschten Helligkeits-, A- und B-Werten für das OKLAB-Modell zurück. |
| static [FromOklaba](../../aspose.svg.drawing/color/fromoklaba/)(*float, float, float, float*) | Gibt eine neue Color mit den gewünschten Helligkeits-, A-, B- und Alphawerten für das OKLAB-Modell zurück. |
| static [FromOklch](../../aspose.svg.drawing/color/fromoklch/)(*float, float, float*) | Gibt eine neue Color mit den gewünschten Leuchtkraft-, Chroma- und Farbtonwerten für das OKLAB-Modell zurück. |
| static [FromOklcha](../../aspose.svg.drawing/color/fromoklcha/)(*float, float, float, float*) | Gibt eine neue Color mit den gewünschten Leuchtkraft-, Chroma-, Farbton- und Alphawerten für das OKLAB-Modell zurück. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb)(*byte, byte, byte*) | Gibt eine neue Color mit den gewünschten ged-, Grün- und Blauwerten zurück. Alle Farbkomponenten müssen im Bereich 0-255 liegen. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb_2)(*float, float, float*) | Gibt eine neue Color mit den gewünschten ged-, Grün- und Blauwerten zurück. Alle Farbkomponenten müssen im Bereich 0-1 liegen. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb_1)(*int, int, int*) | Gibt eine neue Color mit den gewünschten ged-, Grün- und Blauwerten zurück. Alle Farbkomponenten müssen im Bereich 0-255 liegen. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba)(*byte, byte, byte, byte*) | Gibt eine neue Color mit den gewünschten ged-, Grün-, Blau- und Alphawerten zurück. Alle Farbkomponenten müssen im Bereich 0-255 liegen. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba_2)(*float, float, float, float*) | Gibt eine neue Color mit den gewünschten ged-, Grün-, Blau- und Alphawerten zurück. Alle Farbkomponenten müssen im Bereich 0-1 liegen. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba_1)(*int, int, int, int*) | Gibt eine neue Color mit den gewünschten ged-, Grün-, Blau- und Alphawerten zurück. Alle Farbkomponenten müssen im Bereich 0-255 liegen. |
| static [FromString](../../aspose.svg.drawing/color/fromstring/)(*string*) | Parst einen String, der die CSS-Farbe enthält, und gibt eine neue Color zurück. |
| static [FromUint](../../aspose.svg.drawing/color/fromuint/)(*uint*) | Gibt eine neue Color mit dem gewünschten ARGB-Wert zurück. |
| [AddLuminosity](../../aspose.svg.drawing/color/addluminosity/)(*float*) | Erstellt eine Kopie der Color mit der Summe ihrer Leuchtkraft und dem Deltawert. |
| [Convert](../../aspose.svg.drawing/color/convert/)(*[ColorModel](../colormodel/)*) | Gibt Farbkomponenten im Format des angegebenen Farbmodells zurück. |
| override [Equals](../../aspose.svg.drawing/color/equals/)(*object*) | Bestimmt, ob das angegebene `Color` gleich dieser Instanz ist. |
| [GetComplementary](../../aspose.svg.drawing/color/getcomplementary/)() | Gibt eine neue Farbe zurück, die sich auf der gegenüberliegenden Seite des Farbkreises vom Original befindet. |
| override [GetHashCode](../../aspose.svg.drawing/color/gethashcode/)() | Gibt einen Hashcode zurück. |
| [GetHue](../../aspose.svg.drawing/color/gethue/)() | Gibt einen Farbton der Farbe zurück. |
| [GetLuminosity](../../aspose.svg.drawing/color/getluminosity/)() | Gibt eine Leuchtkraft der Farbe zurück. |
| [GetSaturation](../../aspose.svg.drawing/color/getsaturation/)() | Gibt eine Sättigung der Farbe zurück. |
| [ToInt](../../aspose.svg.drawing/color/toint/)() | Kodiert die ARGB-Komponenten der Farbe in einen int. |
| [ToName](../../aspose.svg.drawing/color/toname/)() | Gibt den Namen der Farbe zurück, wenn sie mit einer Farbe in der Liste der benannten CSS-Farben übereinstimmt, sonst einen leeren String. |
| [ToNaturalColorString](../../aspose.svg.drawing/color/tonaturalcolorstring/)(*int*) | Gibt eine natürliche Farbe (NCol) zurück, die mit einem Farbbuchstaben und einer Zahl angegeben wird, um den Abstand (in Prozent) von der Farbe zu bestimmen. |
| [ToRgbaHexString](../../aspose.svg.drawing/color/torgbahexstring/)() | Gibt eine hexadezimale Farbe zurück, angegeben mit: #RRGGBBAA. |
| [ToRgbaString](../../aspose.svg.drawing/color/torgbastring/)() | Gibt einen String zurück, der die RGBA-Farbe enthält, angegeben durch: rgba(R, G, B, A). |
| [ToRgbHexString](../../aspose.svg.drawing/color/torgbhexstring/)() | Gibt eine hexadezimale Farbe zurück, angegeben mit: #RRGGBB. |
| [ToRgbString](../../aspose.svg.drawing/color/torgbstring/)() | Gibt einen String zurück, der die RGB-Farbe enthält, angegeben durch: rgb(R, G, B). |
| override [ToString](../../aspose.svg.drawing/color/tostring/)() | Gibt einen String zurück, der aus den RGBA-Komponentenwerten besteht. |
| [ToUint](../../aspose.svg.drawing/color/touint/)() | Kodiert die ARGB-Komponenten der Farbe in einen unsigned int. |
| [WithAlpha](../../aspose.svg.drawing/color/withalpha/)(*float*) | Erstellt eine Kopie der Farbe mit dem angegebenen Alpha‑Komponenten. |
| [WithHue](../../aspose.svg.drawing/color/withhue/)(*float*) | Erstellt eine Kopie der Farbe mit dem angegebenen Farbton. |
| [WithLuminosity](../../aspose.svg.drawing/color/withluminosity/)(*float*) | Erstellt eine Kopie der Farbe mit der angegebenen Leuchtkraft. |
| [WithSaturation](../../aspose.svg.drawing/color/withsaturation/)(*float*) | Erstellt eine Kopie der Farbe mit der angegebenen Sättigung. |

### Siehe auch

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
