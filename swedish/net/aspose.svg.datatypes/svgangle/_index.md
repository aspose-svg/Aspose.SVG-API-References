---
title: "SVGAngle klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.DataTypes.SVGAngle klass. SVGAngle-gränssnittet motsvarar den grundläggande datatypen angle"
type: docs
weight: 2070
url: /sv/net/aspose.svg.datatypes/svgangle/
---
## SVGAngle class

SVGAngle‑gränssnittet motsvarar den grundläggande datatypen vinkel.

```csharp
public class SVGAngle : SVGValueType
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svgangle/unittype/) { get; } | Typen av värdet som specificeras av en av SVG_ANGLETYPE_*-konstanterna som definieras i detta gränssnitt. |
| [Value](../../aspose.svg.datatypes/svgangle/value/) { get; set; } | Vinkelvärdet som ett flyttal, i grader. Att sätta detta attribut kommer att automatiskt uppdatera valueInSpecifiedUnits och valueAsString för att återspegla denna inställning. |
| [ValueAsString](../../aspose.svg.datatypes/svgangle/valueasstring/) { get; set; } | Vinkelvärdet som en sträng, i de enheter som uttrycks av unitType. Att sätta detta attribut kommer att automatiskt uppdatera value, valueInSpecifiedUnits och unitType för att återspegla denna inställning. |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svgangle/valueinspecifiedunits/) { get; set; } | Vinkelvärdet som ett flyttal, i de enheter som uttrycks av unitType. Att sätta detta attribut kommer att automatiskt uppdatera value och valueAsString för att återspegla denna inställning. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svgangle/converttospecifiedunits/)(*ushort*) | Bevara samma underliggande lagrade värde, men återställ den lagrade enhetsidentifieraren till den angivna unitType. Objektattributen unitType, valueInSpecifiedUnits och valueAsString kan modifieras som ett resultat av denna metod. |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svgangle/newvaluespecifiedunits/)(*ushort, float*) | Återställ värdet som ett tal med en associerad unitType, vilket ersätter värdena för alla attribut på objektet. |
| override [ToString](../../aspose.svg.datatypes/svgangle/tostring/)() | Returnerar en sträng som representerar den här instansen. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.svg.datatypes/svgangle/svg_angletype_deg/) | Enhetstypen sattes explicit till grader. |
| const [SVG_ANGLETYPE_GRAD](../../aspose.svg.datatypes/svgangle/svg_angletype_grad/) | Enhetstypen är radianer. |
| const [SVG_ANGLETYPE_RAD](../../aspose.svg.datatypes/svgangle/svg_angletype_rad/) | Enhetstypen är radianer. |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.svg.datatypes/svgangle/svg_angletype_unknown/) | Enhetstypen är inte en av de fördefinierade enhetstyperna. Det är ogiltigt att försöka definiera ett nytt värde av denna typ eller att försöka byta ett befintligt värde till denna typ. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.svg.datatypes/svgangle/svg_angletype_unspecified/) | Ingen enhetstyp angavs (dvs. ett enhetslöst värde specificerades). För vinklar behandlas ett enhetslöst värde på samma sätt som om grader angavs. |

### Se även

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
