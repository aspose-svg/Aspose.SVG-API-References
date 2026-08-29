---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGAngle ConvertToSpecifiedUnits methode. Behoud dezelfde onderliggende opgeslagen waarde maar reset de opgeslagen eenheidsidentificatie naar het opgegeven unitType. Objectattributen unitType, valueInSpecifiedUnits en valueAsString kunnen als gevolg van deze methode worden aangepast."
type: docs
weight: 50
url: /nl/net/aspose.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Behoud dezelfde onderliggende opgeslagen waarde, maar reset de opgeslagen eenheididentificator naar het opgegeven unitType. Objectattributen unitType, valueInSpecifiedUnits en valueAsString kunnen als gevolg van deze methode worden gewijzigd.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| unitType | UInt16 | Het eenheidstype om naar over te schakelen (bijv. SVG_ANGLETYPE_DEG). |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) Opgetreden als unitType SVG_ANGLETYPE_UNKNOWN is of geen geldige eenheidstype-constante (een van de andere SVG_ANGLETYPE_* constanten die op deze interface zijn gedefinieerd). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Opgetreden wanneer de hoek overeenkomt met een alleen-lezen attribuut of wanneer het object zelf alleen-lezen is. |

### Zie ook

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
