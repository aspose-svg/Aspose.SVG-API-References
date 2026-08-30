---
title: "SVGLength-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.DataTypes.SVGLength-klass. SVGLength-gränssnittet motsvarar den grundläggande datatypen längd. Ett SVGLength-objekt kan betecknas som skrivskyddat, vilket betyder att försök att ändra objektet kommer att resultera i ett undantag som kastas enligt beskrivningen nedan."
type: docs
weight: 2210
url: /sv/net/aspose.svg.datatypes/svglength/
---
## SVGLength class

SVGLength‑gränssnittet motsvarar den grundläggande datatypen längd. Ett SVGLength‑objekt kan markeras som skrivskyddat, vilket innebär att försök att ändra objektet kommer att resultera i ett undantag, enligt beskrivningen nedan.

```csharp
public class SVGLength : SVGValueType
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svglength/unittype/) { get; } | Typen av värdet enligt en av SVG_LENGTHTYPE_*-konstanterna som definieras på detta gränssnitt. |
| [Value](../../aspose.svg.datatypes/svglength/value/) { get; set; } | Värdet som ett flyttal, i användarenheter. Att sätta detta attribut kommer att göra att valueInSpecifiedUnits och valueAsString uppdateras automatiskt för att återspegla denna inställning. |
| [ValueAsString](../../aspose.svg.datatypes/svglength/valueasstring/) { get; set; } | Värdet som en sträng, i de enheter som uttrycks av unitType. Att sätta detta attribut kommer att göra att value, valueInSpecifiedUnits och unitType uppdateras automatiskt för att återspegla denna inställning. |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svglength/valueinspecifiedunits/) { get; set; } | Värdet som ett flyttal, i de enheter som uttrycks av unitType. Att sätta detta attribut kommer att göra att value och valueAsString uppdateras automatiskt för att återspegla denna inställning. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svglength/converttospecifiedunits/)(*ushort*) | Bevara samma underliggande lagrade värde, men återställ den lagrade enhetsidentifieraren till den angivna unitType. Objektattributen unitType, valueInSpecifiedUnits och valueAsString kan modifieras som ett resultat av denna metod. Till exempel, om det ursprungliga värdet var \"0.5cm\" och metoden anropades för att konvertera till millimeter, så skulle unitType ändras till SVG_LENGTHTYPE_MM, valueInSpecifiedUnits ändras till det numeriska värdet 5 och valueAsString ändras till \"5mm\". |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svglength/newvaluespecifiedunits/)(*ushort, float*) | Återställ värdet som ett tal med en associerad unitType, vilket ersätter värdena för alla attribut på objektet. |
| override [ToString](../../aspose.svg.datatypes/svglength/tostring/)() | Returnerar en sträng som representerar den här instansen. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.svg.datatypes/svglength/svg_lengthtype_cm/) | Ett värde angavs med cm-enheterna som definieras i CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../aspose.svg.datatypes/svglength/svg_lengthtype_ems/) | Ett värde angavs med em-enheterna som definieras i CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../aspose.svg.datatypes/svglength/svg_lengthtype_exs/) | Ett värde angavs med ex-enheterna som definieras i CSS2. |
| const [SVG_LENGTHTYPE_IN](../../aspose.svg.datatypes/svglength/svg_lengthtype_in/) | Ett värde angavs med in-enheterna som definieras i CSS2. |
| const [SVG_LENGTHTYPE_MM](../../aspose.svg.datatypes/svglength/svg_lengthtype_mm/) | Ett värde angavs med mm-enheterna som definieras i CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.svg.datatypes/svglength/svg_lengthtype_number/) | Ingen enhetstyp angavs (dvs. ett enhetslöst värde angavs), vilket indikerar ett värde i användarenheter. |
| const [SVG_LENGTHTYPE_PC](../../aspose.svg.datatypes/svglength/svg_lengthtype_pc/) | Ett värde angavs med pc-enheterna som definieras i CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.svg.datatypes/svglength/svg_lengthtype_percentage/) | Ett procentvärde angavs. |
| const [SVG_LENGTHTYPE_PT](../../aspose.svg.datatypes/svglength/svg_lengthtype_pt/) | Ett värde angavs med pt-enheterna som definieras i CSS2. |
| const [SVG_LENGTHTYPE_PX](../../aspose.svg.datatypes/svglength/svg_lengthtype_px/) | Ett värde angavs med px-enheterna som definieras i CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.svg.datatypes/svglength/svg_lengthtype_unknown/) | Enhetstypen är inte en av de fördefinierade enhetstyperna. Det är ogiltigt att försöka definiera ett nytt värde av denna typ eller att försöka byta ett befintligt värde till denna typ. |

### Se även

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
