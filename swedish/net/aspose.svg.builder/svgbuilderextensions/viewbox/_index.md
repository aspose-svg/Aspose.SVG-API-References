---
title: "SVGBuilderExtensions.ViewBox"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions ViewBox-metoden. Ställer in viewBox-attributet för ett SVG-element"
type: docs
weight: 2300
url: /sv/net/aspose.svg.builder/svgbuilderextensions/viewbox/
---
## SVGBuilderExtensions.ViewBox<TBuilder> method

Ställer in attributet 'viewBox' för ett SVG-element.

```csharp
public static TBuilder ViewBox<TBuilder>(this TBuilder builder, double minX, double minY, 
    double width, double height)
    where TBuilder : ISVGElementBuilder, IViewBoxAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| minX | Den minsta X-koordinaten för viewBox. |
| minY | Den minsta Y-koordinaten för viewBox. |
| width | Bredden på viewBox. |
| height | Höjden på viewBox. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IViewBoxAttributeSetter](../../iviewboxattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
