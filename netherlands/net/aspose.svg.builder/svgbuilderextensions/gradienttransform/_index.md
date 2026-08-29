---
title: "SVGBuilderExtensions.GradientTransform"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions GradientTransform-methode. Stelt het gradientTransform-attribuut in voor een gradient‑element"
type: docs
weight: 980
url: /nl/net/aspose.svg.builder/svgbuilderextensions/gradienttransform/
---
## SVGBuilderExtensions.GradientTransform<TBuilder> method

Stelt het 'gradientTransform' attribuut voor een gradient-element in.

```csharp
public static TBuilder GradientTransform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbouwer waarop het attribuut wordt toegepast. |
| configureren | Een functie om de SVG-transformatie-bouwer te configureren. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
