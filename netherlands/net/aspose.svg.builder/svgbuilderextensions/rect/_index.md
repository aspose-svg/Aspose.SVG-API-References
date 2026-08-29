---
title: "SVGBuilderExtensions.Rect"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions Rect-methode. Stelt de x-, y-, breedte- en hoogte‑attributen in voor een SVG‑element om een rechthoek te definiëren."
type: docs
weight: 1920
url: /nl/net/aspose.svg.builder/svgbuilderextensions/rect/
---
## SVGBuilderExtensions.Rect<TBuilder> method

Stelt de 'x', 'y', 'width' en 'height' attributen in voor een SVG‑element om een rechthoek te definiëren.

```csharp
public static TBuilder Rect<TBuilder>(this TBuilder builder, double x, double y, double width, 
    double height, LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRectAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| x | De x‑coördinaat van de rechthoek. |
| y | De y‑coördinaat van de rechthoek. |
| width | De breedte van de rechthoek. |
| height | De hoogte van de rechthoek. |
| type | Het type lengtemeting voor alle dimensies (standaard is pixels). |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRectAttributeSetter](../../irectattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
