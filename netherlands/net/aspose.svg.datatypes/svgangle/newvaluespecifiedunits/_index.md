---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGAngle NewValueSpecifiedUnits method. Reset de waarde als een getal met een bijbehorend unitType, waardoor de waarden voor alle attributen op het object worden vervangen."
type: docs
weight: 60
url: /nl/net/aspose.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Reset de waarde als een getal met een bijbehorend unitType, waardoor de waarden voor alle attributen van het object worden vervangen.

```csharp
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newUnitType | UInt16 | Het eenheidstype voor de waarde (bijv. SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | De hoekwaarde. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) Opgetreden als unitType SVG_ANGLETYPE_UNKNOWN is of geen geldige eenheidstype-constante (een van de andere SVG_ANGLETYPE_* constanten die op deze interface zijn gedefinieerd). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Opgetreden wanneer de hoek overeenkomt met een alleen-lezen attribuut of wanneer het object zelf alleen-lezen is. |

### Zie ook

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
