---
title: "SVGPoint Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.DataTypes.SVGPoint klasse. Veel van de SVG DOM‑interfaces verwijzen naar objecten van de klasse SVGPoint. Een SVGPoint is een x‑y‑coördinaatpaar. Wanneer het wordt gebruikt in matrixbewerkingen, wordt een SVGPoint behandeld als een vector van de vorm x y 1. Als een SVGRect‑object als alleen‑lezen is gemarkeerd, zal een poging om een van zijn attributen toe te wijzen resulteren in een gegooide uitzondering."
type: docs
weight: 2260
url: /nl/net/aspose.svg.datatypes/svgpoint/
---
## SVGPoint class

Veel van de SVG‑DOM‑interfaces verwijzen naar objecten van de klasse SVGPoint. Een SVGPoint is een (x, y) coördinaatpaar. Wanneer gebruikt in matrixbewerkingen, wordt een SVGPoint behandeld als een vector van de vorm: [x] [y] [1] Als een SVGRect‑object als alleen‑lezen wordt gemarkeerd, zal een poging om een van zijn attributen toe te wijzen een uitzondering veroorzaken.

```csharp
public class SVGPoint : SVGValueType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [X](../../aspose.svg.datatypes/svgpoint/x/) { get; set; } | De X-coördinaat. |
| [Y](../../aspose.svg.datatypes/svgpoint/y/) { get; set; } | De Y-coördinaat. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Vrijgeeft niet‑beheerde en - optioneel - beheerde bronnen. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [MatrixTransform](../../aspose.svg.datatypes/svgpoint/matrixtransform/)(*[SVGMatrix](../svgmatrix/)*) | Past een 2x3-matrixtransformatie toe op dit SVGPoint‑object en retourneert een nieuw, getransformeerd SVGPoint‑object: newpoint = matrix* thispoint |
| override [ToString](../../aspose.svg.datatypes/svgpoint/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |

### Zie ook

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
