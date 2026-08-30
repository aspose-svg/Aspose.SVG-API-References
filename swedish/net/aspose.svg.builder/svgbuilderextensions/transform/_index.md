---
title: "SVGBuilderExtensions.Transform"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions Transform-metod. Ställer in transform-attributet för ett SVG-element"
type: docs
weight: 2260
url: /sv/net/aspose.svg.builder/svgbuilderextensions/transform/
---
## SVGBuilderExtensions.Transform<TBuilder> method

Ställer in attributet 'transform' för ett SVG-element.

```csharp
public static TBuilder Transform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, ITransformAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | En funktion för att konfigurera SVG‑transformen. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITransformAttributeSetter](../../itransformattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
