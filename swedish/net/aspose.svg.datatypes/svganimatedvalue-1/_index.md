---
title: "SVGAnimatedValueT klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.DataTypes.SVGAnimatedValue1T klass. Används för attribut av typer som kan animeras"
type: docs
weight: 2200
url: /sv/net/aspose.svg.datatypes/svganimatedvalue-1/
---
## SVGAnimatedValue<T> class

Används för attribut av typer som kan animeras.

```csharp
public abstract class SVGAnimatedValue<T> : SVGValueType
```

| Parameter | Beskrivning |
| --- | --- |
| T | Det SVG Value-objektet. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [AnimVal](../../aspose.svg.datatypes/svganimatedvalue-1/animval/) { get; } | Om det angivna attributet eller egenskapen är under animation, innehåller det det aktuella animerade värdet för attributet eller egenskapen. Om det angivna attributet eller egenskapen för närvarande inte är animerad, innehåller det samma värde som baseVal. |
| [BaseVal](../../aspose.svg.datatypes/svganimatedvalue-1/baseval/) { get; set; } | Grundvärdet för det angivna attributet innan några animationer tillämpas. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |

### Se även

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
