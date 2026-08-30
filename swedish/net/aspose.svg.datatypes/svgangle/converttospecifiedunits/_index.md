---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGAngle ConvertToSpecifiedUnits-metod. Bevarar samma underliggande lagrade värde men återställer den lagrade enhetsidentifieraren till den angivna unitType. Objektattributen unitType, valueInSpecifiedUnits och valueAsString kan modifieras som ett resultat av denna metod."
type: docs
weight: 50
url: /sv/net/aspose.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Bevara samma underliggande lagrade värde, men återställ den lagrade enhetsidentifieraren till den angivna unitType. Objektattributen unitType, valueInSpecifiedUnits och valueAsString kan modifieras som ett resultat av denna metod.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| unitType | UInt16 | Enhetstypen att byta till (t.ex. SVG_ANGLETYPE_DEG). |

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) Uppstår om unitType är SVG_ANGLETYPE_UNKNOWN eller inte är en giltig enhetstypkonstant (en av de andra SVG_ANGLETYPE_*‑konstanterna som definieras på detta gränssnitt). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Uppstår när vinkeln motsvarar ett skrivskyddat attribut eller när själva objektet är skrivskyddat. |

### Se även

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
