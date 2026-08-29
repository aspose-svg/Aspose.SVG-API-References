---
title: "SVGBuilderExtensions.ViewBox"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions ViewBox-methode. Stelt het viewBox-attribuut in voor een SVG-element"
type: docs
weight: 2300
url: /nl/net/aspose.svg.builder/svgbuilderextensions/viewbox/
---
## SVGBuilderExtensions.ViewBox<TBuilder> method

Stelt het 'viewBox' attribuut in voor een SVG-element.

```csharp
public static TBuilder ViewBox<TBuilder>(this TBuilder builder, double minX, double minY, 
    double width, double height)
    where TBuilder : ISVGElementBuilder, IViewBoxAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| minX | De minimum X-coördinaat van de viewBox. |
| minY | De minimum Y-coördinaat van de viewBox. |
| width | De breedte van de viewBox. |
| height | De hoogte van de viewBox. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IViewBoxAttributeSetter](../../iviewboxattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
