---
title: "SVGBuilderExtensions.Rect"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions Rect-Methode. Setzt die x-, y-, width- und height-Attribute eines SVG-Elements, um ein Rechteck zu definieren."
type: docs
weight: 1920
url: /de/net/aspose.svg.builder/svgbuilderextensions/rect/
---
## SVGBuilderExtensions.Rect<TBuilder> method

Setzt die Attribute 'x', 'y', 'width' und 'height' für ein SVG-Element, um ein Rechteck zu definieren.

```csharp
public static TBuilder Rect<TBuilder>(this TBuilder builder, double x, double y, double width, 
    double height, LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRectAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| x | Die x-Koordinate des Rechtecks. |
| y | Die y-Koordinate des Rechtecks. |
| width | Die Breite des Rechtecks. |
| height | Die Höhe des Rechtecks. |
| type | Der Typ der Längenmessung für alle Dimensionen (Standard ist Pixel). |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRectAttributeSetter](../../irectattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
