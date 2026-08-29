---
title: "SVGBuilderExtensions.Transform"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions Transform-methode. Stelt het transform‑attribuut in voor een SVG-element."
type: docs
weight: 2260
url: /nl/net/aspose.svg.builder/svgbuilderextensions/transform/
---
## SVGBuilderExtensions.Transform<TBuilder> method

Stelt het 'transform' attribuut in voor een SVG-element.

```csharp
public static TBuilder Transform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, ITransformAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | Een functie om de SVG-transformatie te configureren. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITransformAttributeSetter](../../itransformattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
