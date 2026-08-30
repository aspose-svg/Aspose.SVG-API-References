---
title: "SVGBuilderExtensions.Rect"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions Rect-metoden. Ställer in x-, y-, bredd- och höjdattributen för ett SVG-element för att definiera en rektangel"
type: docs
weight: 1920
url: /sv/net/aspose.svg.builder/svgbuilderextensions/rect/
---
## SVGBuilderExtensions.Rect<TBuilder> method

Ställer in 'x', 'y', 'width' och 'height'-attributen för ett SVG-element för att definiera en rektangel.

```csharp
public static TBuilder Rect<TBuilder>(this TBuilder builder, double x, double y, double width, 
    double height, LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRectAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| x | X-koordinaten för rektangeln. |
| y | Y-koordinaten för rektangeln. |
| width | Bredden på rektangeln. |
| height | Höjden på rektangeln. |
| type | Typen av längdmätning för alla dimensioner (standard är pixlar). |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRectAttributeSetter](../../irectattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
