---
title: "SVGLength Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.DataTypes.SVGLength klasse. De SVGLength interface komt overeen met het basisgegevenstype lengte. Een SVGLength‑object kan als alleen‑lezen worden aangemerkt, wat betekent dat pogingen om het object te wijzigen resulteren in een uitzondering die hieronder wordt beschreven."
type: docs
weight: 2210
url: /nl/net/aspose.svg.datatypes/svglength/
---
## SVGLength class

De SVGLength‑interface komt overeen met het basistype length. Een SVGLength‑object kan als alleen‑lezen worden gemarkeerd, wat betekent dat pogingen om het object te wijzigen een uitzondering veroorzaken, zoals hieronder beschreven.

```csharp
public class SVGLength : SVGValueType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svglength/unittype/) { get; } | Het type van de waarde zoals gespecificeerd door een van de SVG_LENGTHTYPE_* constanten die op deze interface zijn gedefinieerd. |
| [Value](../../aspose.svg.datatypes/svglength/value/) { get; set; } | De waarde als een zwevend‑kommagetal, in gebruikers‑eenheden. Het instellen van dit attribuut zal ervoor zorgen dat valueInSpecifiedUnits en valueAsString automatisch worden bijgewerkt om deze instelling weer te geven. |
| [ValueAsString](../../aspose.svg.datatypes/svglength/valueasstring/) { get; set; } | De waarde als een tekenreeks, in de eenheden die door unitType worden uitgedrukt. Het instellen van dit attribuut zal ervoor zorgen dat value, valueInSpecifiedUnits en unitType automatisch worden bijgewerkt om deze instelling weer te geven. |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svglength/valueinspecifiedunits/) { get; set; } | De waarde als een zwevend‑kommagetal, in de eenheden die door unitType worden uitgedrukt. Het instellen van dit attribuut zal ervoor zorgen dat value en valueAsString automatisch worden bijgewerkt om deze instelling weer te geven. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svglength/converttospecifiedunits/)(*ushort*) | Behoud dezelfde onderliggende opgeslagen waarde, maar reset de opgeslagen eenheids‑identificator naar het opgegeven unitType. Objectattributen unitType, valueInSpecifiedUnits en valueAsString kunnen als gevolg van deze methode worden aangepast. Bijvoorbeeld, als de oorspronkelijke waarde "0.5cm" was en de methode werd aangeroepen om naar millimeters te converteren, dan zou unitType worden gewijzigd naar SVG_LENGTHTYPE_MM, valueInSpecifiedUnits zou worden gewijzigd naar de numerieke waarde 5 en valueAsString zou worden gewijzigd naar "5mm". |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Vrijgeeft niet‑beheerde en - optioneel - beheerde bronnen. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svglength/newvaluespecifiedunits/)(*ushort, float*) | Reset de waarde als een getal met een bijbehorend unitType, waardoor de waarden voor alle attributen van het object worden vervangen. |
| override [ToString](../../aspose.svg.datatypes/svglength/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.svg.datatypes/svglength/svg_lengthtype_cm/) | Er werd een waarde gespecificeerd met de cm‑eenheden gedefinieerd in CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../aspose.svg.datatypes/svglength/svg_lengthtype_ems/) | Er werd een waarde gespecificeerd met de em‑eenheden gedefinieerd in CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../aspose.svg.datatypes/svglength/svg_lengthtype_exs/) | Er werd een waarde gespecificeerd met de ex‑eenheden gedefinieerd in CSS2. |
| const [SVG_LENGTHTYPE_IN](../../aspose.svg.datatypes/svglength/svg_lengthtype_in/) | Er werd een waarde gespecificeerd met de in‑eenheden gedefinieerd in CSS2. |
| const [SVG_LENGTHTYPE_MM](../../aspose.svg.datatypes/svglength/svg_lengthtype_mm/) | Er werd een waarde gespecificeerd met de mm‑eenheden gedefinieerd in CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.svg.datatypes/svglength/svg_lengthtype_number/) | Er werd geen eenheidstype opgegeven (d.w.z. een eenheidsloze waarde werd gespecificeerd), wat een waarde in gebruikers‑eenheden aangeeft. |
| const [SVG_LENGTHTYPE_PC](../../aspose.svg.datatypes/svglength/svg_lengthtype_pc/) | Er werd een waarde gespecificeerd met de pc‑eenheden gedefinieerd in CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.svg.datatypes/svglength/svg_lengthtype_percentage/) | Er werd een procentuele waarde gespecificeerd. |
| const [SVG_LENGTHTYPE_PT](../../aspose.svg.datatypes/svglength/svg_lengthtype_pt/) | Er werd een waarde gespecificeerd met de pt‑eenheden gedefinieerd in CSS2. |
| const [SVG_LENGTHTYPE_PX](../../aspose.svg.datatypes/svglength/svg_lengthtype_px/) | Er werd een waarde gespecificeerd met de px‑eenheden gedefinieerd in CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.svg.datatypes/svglength/svg_lengthtype_unknown/) | Het eenheidstype is geen van de vooraf gedefinieerde eenheidstypen. Het is ongeldig om te proberen een nieuwe waarde van dit type te definiëren of om een bestaande waarde naar dit type te wijzigen. |

### Zie ook

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
