---
title: "SVGBuilderExtensions.SetPreserveAspectRatio"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions SetPreserveAspectRatio metod. Ställer in preserveAspectRatio‑attributet för ett SVG‑element"
type: docs
weight: 2020
url: /sv/net/aspose.svg.builder/svgbuilderextensions/setpreserveaspectratio/
---
## SVGBuilderExtensions.SetPreserveAspectRatio<TBuilder> method

Ställer in attributet 'preserveAspectRatio' för ett SVG-element.

```csharp
public static TBuilder SetPreserveAspectRatio<TBuilder>(this TBuilder builder, 
    AspectRatioAlign align, AspectRatioScaling meetOrSlice = AspectRatioScaling.Meet)
    where TBuilder : ISVGElementBuilder, IPreserveAspectRatioAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| align | Inställningen för justering av bildförhållandet. |
| meetOrSlice | Anger hur ett bildförhållande bevaras (standard är 'Meet'). |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [AspectRatioAlign](../../aspectratioalign/)
* enum [AspectRatioScaling](../../aspectratioscaling/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../../ipreserveaspectratioattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
