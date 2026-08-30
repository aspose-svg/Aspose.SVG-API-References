---
title: "SVGBuilderExtensions.GradientTransform"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions GradientTransform-metod. Ställer in gradientTransform-attributet för ett gradientelement"
type: docs
weight: 980
url: /sv/net/aspose.svg.builder/svgbuilderextensions/gradienttransform/
---
## SVGBuilderExtensions.GradientTransform<TBuilder> method

Ställer in attributet 'gradientTransform' för ett gradientelement.

```csharp
public static TBuilder GradientTransform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren som attributet tillämpas på. |
| konfigurera | En funktion för att konfigurera SVG-transformbyggaren. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
