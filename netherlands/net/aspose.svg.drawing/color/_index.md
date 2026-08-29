---
title: "Color-klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Drawing.Color class. De Color-klasse stelt u in staat kleuren op te geven als Red-Green-Blue RGB-waarden, Hue-Saturation-Luminosity HSL-waarden, Hue-Saturation-Value HSV-waarden, Hue-Whiteness-Blackness HWB-waarden, lightness-A-B LAB-waarden, Luminance-Chroma-Hue LCH-waarden, Cyan-Magenta-Yellow-Key CMYK-waarden, Natural colors NCOL-waarden of met een kleurnaam. Een Alpha-kanaal is ook beschikbaar om transparantie aan te geven."
type: docs
weight: 3390
url: /nl/net/aspose.svg.drawing/color/
---
## Color class

De Color-klasse stelt je in staat kleuren op te geven als Red-Green-Blue (RGB)-waarden, Hue-Saturation-Luminosity (HSL)-waarden, Hue-Saturation-Value (HSV)-waarden, Hue-Whiteness-Blackness (HWB)-waarden, lightness-A-B (LAB)-waarden, Luminance-Chroma-Hue (LCH)-waarden, Cyan-Magenta-Yellow-Key (CMYK)-waarden, Natural colors (NCOL)-waarden, of met een kleurnaam. Een Alpha-kanaal is ook beschikbaar om transparantie aan te geven.

```csharp
public class Color
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Color](color/#constructor)() | Initialiseert een nieuw exemplaar van de `Color`-klasse. Standaard is de kleur zwart. |
| [Color](color/#constructor_1)(*byte, byte, byte*) | Initialiseert een nieuw exemplaar van de `Color`-klasse. Alle kleurcomponenten moeten binnen het bereik 0-255 liggen. |
| [Color](color/#constructor_5)(*float, float, float*) | Initialiseert een nieuw exemplaar van de `Color`-klasse. Alle kleurcomponenten moeten binnen het bereik 0-1 liggen. |
| [Color](color/#constructor_3)(*int, int, int*) | Initialiseert een nieuw exemplaar van de `Color`-klasse. Alle kleurcomponenten moeten binnen het bereik 0-255 liggen. |
| [Color](color/#constructor_2)(*byte, byte, byte, byte*) | Initialiseert een nieuw exemplaar van de `Color`-klasse. Alle kleurcomponenten moeten binnen het bereik 0-255 liggen. |
| [Color](color/#constructor_6)(*float, float, float, float*) | Initialiseert een nieuw exemplaar van de `Color`-klasse. Alle kleurcomponenten moeten binnen het bereik 0-1 liggen. |
| [Color](color/#constructor_4)(*int, int, int, int*) | Initialiseert een nieuw exemplaar van de `Color`-klasse. Alle kleurcomponenten moeten binnen het bereik 0-255 liggen. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Alpha](../../aspose.svg.drawing/color/alpha/) { get; } | Stelt de alfa-component van de kleur voor. |
| [Blue](../../aspose.svg.drawing/color/blue/) { get; } | Stelt de blauwe component van de kleur voor. |
| [Green](../../aspose.svg.drawing/color/green/) { get; } | Stelt de groene component van de kleur voor. |
| [Red](../../aspose.svg.drawing/color/red/) { get; } | Stelt de rode component van de kleur voor. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromCmyk](../../aspose.svg.drawing/color/fromcmyk/)(*float, float, float, float*) | Retourneert een nieuwe Color met de gevraagde cyan, magenta, yellow, key (black) waarden. |
| static [FromCmyka](../../aspose.svg.drawing/color/fromcmyka/)(*float, float, float, float, float*) | Retourneert een nieuwe Color met de gevraagde cyan, magenta, yellow, key (black), alpha waarden. |
| static [FromGray](../../aspose.svg.drawing/color/fromgray/)(*float*) | Retourneert een nieuwe Color met de gevraagde gray waarde. |
| static [FromHsl](../../aspose.svg.drawing/color/fromhsl/)(*float, float, float*) | Retourneert een nieuwe Color met de gevraagde hue, saturation, saturation waarden. |
| static [FromHsla](../../aspose.svg.drawing/color/fromhsla/)(*float, float, float, float*) | Retourneert een nieuwe Color met de gevraagde hue, saturation, saturation, alpha waarden. |
| static [FromHsv](../../aspose.svg.drawing/color/fromhsv/)(*float, float, float*) | Retourneert een nieuwe Color met de gevraagde hue, saturation, value. |
| static [FromHsva](../../aspose.svg.drawing/color/fromhsva/)(*float, float, float, float*) | Retourneert een nieuwe Color met de gevraagde hue, saturation, value, alpha. |
| static [FromHwb](../../aspose.svg.drawing/color/fromhwb/)(*float, float, float*) | Retourneert een nieuwe Color met de gevraagde hue, whiteness, blackness waarden. |
| static [FromHwba](../../aspose.svg.drawing/color/fromhwba/)(*float, float, float, float*) | Retourneert een nieuwe Color met de gevraagde hue, whiteness, blackness waarden. |
| static [FromInt](../../aspose.svg.drawing/color/fromint/)(*int*) | Retourneert een nieuwe Color met de gevraagde ARGB waarde. |
| static [FromLab](../../aspose.svg.drawing/color/fromlab/)(*float, float, float*) | Retourneert een nieuwe Color met de gevraagde lightness, A, B waarden. |
| static [FromLaba](../../aspose.svg.drawing/color/fromlaba/)(*float, float, float, float*) | Retourneert een nieuwe Color met de gevraagde lightness, A, B, alpha waarden. |
| static [FromLch](../../aspose.svg.drawing/color/fromlch/)(*float, float, float*) | Retourneert een nieuwe Color met de gevraagde luminance, chroma, hue waarden. |
| static [FromLcha](../../aspose.svg.drawing/color/fromlcha/)(*float, float, float, float*) | Retourneert een nieuwe Color met de gevraagde luminance, chroma, hue, alpha waarden. |
| static [FromOklab](../../aspose.svg.drawing/color/fromoklab/)(*float, float, float*) | Retourneert een nieuwe Color met de gevraagde lightness, A, B waarden voor het OKLAB-model. |
| static [FromOklaba](../../aspose.svg.drawing/color/fromoklaba/)(*float, float, float, float*) | Retourneert een nieuwe Color met de gevraagde lightness, A, B, alpha waarden voor het OKLAB-model. |
| static [FromOklch](../../aspose.svg.drawing/color/fromoklch/)(*float, float, float*) | Retourneert een nieuwe Color met de gevraagde luminance, chroma, hue waarden voor het OKLAB-model. |
| static [FromOklcha](../../aspose.svg.drawing/color/fromoklcha/)(*float, float, float, float*) | Retourneert een nieuwe Color met de gevraagde luminance, chroma, hue, alpha waarden voor het OKLAB-model. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb)(*byte, byte, byte*) | Retourneert een nieuwe Color met de gevraagde ged, green, blue waarden. Alle kleurcomponenten moeten binnen het bereik 0-255 liggen. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb_2)(*float, float, float*) | Retourneert een nieuwe Color met de gevraagde ged, green, blue waarden. Alle kleurcomponenten moeten binnen het bereik 0-1 liggen. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb_1)(*int, int, int*) | Retourneert een nieuwe Color met de gevraagde ged, green, blue waarden. Alle kleurcomponenten moeten binnen het bereik 0-255 liggen. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba)(*byte, byte, byte, byte*) | Retourneert een nieuwe Color met de gevraagde ged, green, blue, alpha waarden. Alle kleurcomponenten moeten binnen het bereik 0-255 liggen. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba_2)(*float, float, float, float*) | Retourneert een nieuwe Color met de gevraagde ged, green, blue, alpha waarden. Alle kleurcomponenten moeten binnen het bereik 0-1 liggen. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba_1)(*int, int, int, int*) | Retourneert een nieuwe Color met de gevraagde ged, green, blue, alpha waarden. Alle kleurcomponenten moeten binnen het bereik 0-255 liggen. |
| static [FromString](../../aspose.svg.drawing/color/fromstring/)(*string*) | Parseert een string die de CSS-kleur bevat en retourneert een nieuwe Color. |
| static [FromUint](../../aspose.svg.drawing/color/fromuint/)(*uint*) | Retourneert een nieuwe Color met de gevraagde ARGB waarde. |
| [AddLuminosity](../../aspose.svg.drawing/color/addluminosity/)(*float*) | Maakt een kopie van de Color met de som van zijn luminosity en de delta-waarde. |
| [Convert](../../aspose.svg.drawing/color/convert/)(*[ColorModel](../colormodel/)*) | Retourneert kleurcomponenten in het formaat van het opgegeven kleurmodel. |
| override [Equals](../../aspose.svg.drawing/color/equals/)(*object*) | Bepaalt of de opgegeven `Color` gelijk is aan deze instantie. |
| [GetComplementary](../../aspose.svg.drawing/color/getcomplementary/)() | Retourneert een nieuwe kleur die zich aan de tegenovergestelde kant van het kleurenwiel bevindt ten opzichte van het origineel. |
| override [GetHashCode](../../aspose.svg.drawing/color/gethashcode/)() | Retourneert een hashcode. |
| [GetHue](../../aspose.svg.drawing/color/gethue/)() | Retourneert een tint van de kleur. |
| [GetLuminosity](../../aspose.svg.drawing/color/getluminosity/)() | Retourneert een luminantie van de kleur. |
| [GetSaturation](../../aspose.svg.drawing/color/getsaturation/)() | Retourneert een verzadiging van de kleur. |
| [ToInt](../../aspose.svg.drawing/color/toint/)() | Encodeert de ARGB-componenten van de kleur naar een int. |
| [ToName](../../aspose.svg.drawing/color/toname/)() | Retourneert de naam van de kleur als deze overeenkomt met een kleur in de lijst met CSS-naamkleuren, of een lege string. |
| [ToNaturalColorString](../../aspose.svg.drawing/color/tonaturalcolorstring/)(*int*) | Retourneert een Natural colors (NCol) gespecificeerde kleur met een kleurletter en een getal om de afstand (in procent) van de kleur te specificeren. |
| [ToRgbaHexString](../../aspose.svg.drawing/color/torgbahexstring/)() | Retourneert een hexadecimale kleur gespecificeerd met: #RRGGBBAA. |
| [ToRgbaString](../../aspose.svg.drawing/color/torgbastring/)() | Retourneert een string die de RGBA-kleur bevat gespecificeerd door: rgba(R, G, B, A). |
| [ToRgbHexString](../../aspose.svg.drawing/color/torgbhexstring/)() | Retourneert een hexadecimale kleur gespecificeerd met: #RRGGBB. |
| [ToRgbString](../../aspose.svg.drawing/color/torgbstring/)() | Retourneert een string die de RGB-kleur bevat gespecificeerd door: rgb(R, G, B). |
| override [ToString](../../aspose.svg.drawing/color/tostring/)() | Retourneert een string die bestaat uit de RGBA-componentwaarden. |
| [ToUint](../../aspose.svg.drawing/color/touint/)() | Encodeert de ARGB-componenten van de kleur naar een unsigned int. |
| [WithAlpha](../../aspose.svg.drawing/color/withalpha/)(*float*) | Maakt een kopie van de kleur met opgegeven alfacomponent. |
| [WithHue](../../aspose.svg.drawing/color/withhue/)(*float*) | Maakt een kopie van de kleur met opgegeven tint. |
| [WithLuminosity](../../aspose.svg.drawing/color/withluminosity/)(*float*) | Maakt een kopie van de kleur met opgegeven luminantie. |
| [WithSaturation](../../aspose.svg.drawing/color/withsaturation/)(*float*) | Maakt een kopie van de kleur met opgegeven verzadiging. |

### Zie ook

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
