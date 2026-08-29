---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGLength NewValueSpecifiedUnits-methode. Reset de waarde als een getal met een bijbehorend unitType, waardoor de waarden voor alle attributen op het object worden vervangen."
type: docs
weight: 60
url: /nl/net/aspose.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Reset de waarde als een getal met een bijbehorend unitType, waardoor de waarden voor alle attributen van het object worden vervangen.

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| unitType | UInt16 | Het eenheidstype voor de waarde. |
| valueInSpecifiedUnits | Single | De nieuwe waarde.. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) Wordt opgegooid als unitType SVG_LENGTHTYPE_UNKNOWN is of geen geldige eenheidstype-constante (een van de andere SVG_LENGTHTYPE_* constanten die op deze interface zijn gedefinieerd). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Opgetreden wanneer de lengte overeenkomt met een alleen-lezen attribuut of wanneer het object zelf alleen-lezen is. |

### Zie ook

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
