---
title: "SVGBuilderExtensions.GradientUnits"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions GradientUnits-metoden. Ställer in gradientUnits-attributet för ett gradient-element"
type: docs
weight: 990
url: /sv/net/aspose.svg.builder/svgbuilderextensions/gradientunits/
---
## SVGBuilderExtensions.GradientUnits<TBuilder> method

Ställer in attributet 'gradientUnits' för ett gradientelement.

```csharp
public static TBuilder GradientUnits<TBuilder>(this TBuilder builder, CoordinateUnits units)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren som attributet tillämpas på. |
| enheter | Koordinatenheterna för gradienten (userSpaceOnUse eller objectBoundingBox). |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [CoordinateUnits](../../coordinateunits/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
