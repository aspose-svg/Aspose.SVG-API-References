---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGLength ConvertToSpecifiedUnits‑metod. Bevarar samma underliggande lagrade värde men återställer den lagrade enhetsidentifieraren till den angivna unitType. Objektattributen unitType, valueInSpecifiedUnits och valueAsString kan modifieras som ett resultat av denna metod. Till exempel, om det ursprungliga värdet var 0,5 cm och metoden anropas för att konvertera till millimeter, så skulle unitType ändras till SVG_LENGTHTYPE_MM, valueInSpecifiedUnits ändras till det numeriska värdet 5 och valueAsString ändras till 5mm."
type: docs
weight: 50
url: /sv/net/aspose.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Bevara samma underliggande lagrade värde, men återställ den lagrade enhetsidentifieraren till den angivna unitType. Objektattributen unitType, valueInSpecifiedUnits och valueAsString kan modifieras som ett resultat av denna metod. Till exempel, om det ursprungliga värdet var \"0.5cm\" och metoden anropades för att konvertera till millimeter, så skulle unitType ändras till SVG_LENGTHTYPE_MM, valueInSpecifiedUnits ändras till det numeriska värdet 5 och valueAsString ändras till \"5mm\".

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| unitType | UInt16 | Enhetstypen att byta till (t.ex. SVG_LENGTHTYPE_MM). |

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) kastas om unitType är SVG_LENGTHTYPE_UNKNOWN eller inte är en giltig enhetstypkonstant (en av de andra SVG_LENGTHTYPE_*-konstanterna som definieras på detta gränssnitt). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Uppstår när längden motsvarar ett skrivskyddat attribut eller när objektet självt är skrivskyddat. |

### Se även

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
