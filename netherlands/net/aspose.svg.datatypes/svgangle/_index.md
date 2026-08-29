---
title: "SVGAngle Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.DataTypes.SVGAngle klasse. De SVGAngle-interface komt overeen met het basistype hoek"
type: docs
weight: 2070
url: /nl/net/aspose.svg.datatypes/svgangle/
---
## SVGAngle class

De SVGAngle‑interface komt overeen met het basistype hoek.

```csharp
public class SVGAngle : SVGValueType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svgangle/unittype/) { get; } | Het type van de waarde zoals gespecificeerd door een van de SVG_ANGLETYPE_* constanten die op deze interface zijn gedefinieerd. |
| [Value](../../aspose.svg.datatypes/svgangle/value/) { get; set; } | De hoekswaarde als een zwevendekommagetal, in graden. Het instellen van dit attribuut zorgt ervoor dat valueInSpecifiedUnits en valueAsString automatisch worden bijgewerkt om deze instelling weer te geven. |
| [ValueAsString](../../aspose.svg.datatypes/svgangle/valueasstring/) { get; set; } | De hoekswaarde als een tekenreeks, in de eenheden die worden uitgedrukt door unitType. Het instellen van dit attribuut zorgt ervoor dat value, valueInSpecifiedUnits en unitType automatisch worden bijgewerkt om deze instelling weer te geven. |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svgangle/valueinspecifiedunits/) { get; set; } | De hoekswaarde als een zwevendekommagetal, in de eenheden die worden uitgedrukt door unitType. Het instellen van dit attribuut zorgt ervoor dat value en valueAsString automatisch worden bijgewerkt om deze instelling weer te geven. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svgangle/converttospecifiedunits/)(*ushort*) | Behoud dezelfde onderliggende opgeslagen waarde, maar reset de opgeslagen eenheididentificator naar het opgegeven unitType. Objectattributen unitType, valueInSpecifiedUnits en valueAsString kunnen als gevolg van deze methode worden gewijzigd. |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Vrijgeeft niet‑beheerde en - optioneel - beheerde bronnen. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svgangle/newvaluespecifiedunits/)(*ushort, float*) | Reset de waarde als een getal met een bijbehorend unitType, waardoor de waarden voor alle attributen van het object worden vervangen. |
| override [ToString](../../aspose.svg.datatypes/svgangle/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.svg.datatypes/svgangle/svg_angletype_deg/) | Het eenheidstype is expliciet ingesteld op graden. |
| const [SVG_ANGLETYPE_GRAD](../../aspose.svg.datatypes/svgangle/svg_angletype_grad/) | Het eenheidstype is radialen. |
| const [SVG_ANGLETYPE_RAD](../../aspose.svg.datatypes/svgangle/svg_angletype_rad/) | Het eenheidstype is radialen. |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.svg.datatypes/svgangle/svg_angletype_unknown/) | Het eenheidstype is geen van de vooraf gedefinieerde eenheidstypen. Het is ongeldig om te proberen een nieuwe waarde van dit type te definiëren of om een bestaande waarde naar dit type te wijzigen. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.svg.datatypes/svgangle/svg_angletype_unspecified/) | Er is geen eenheidstype opgegeven (d.w.z. er is een eenheidsloze waarde gespecificeerd). Voor hoeken wordt een eenheidsloze waarde behandeld alsof graden zijn opgegeven. |

### Zie ook

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
