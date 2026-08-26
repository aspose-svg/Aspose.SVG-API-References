---
title: "SVGBuilderExtensions.ViewBox"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions ViewBox-Methode. Setzt das viewBox-Attribut für ein SVG-Element."
type: docs
weight: 2300
url: /de/net/aspose.svg.builder/svgbuilderextensions/viewbox/
---
## SVGBuilderExtensions.ViewBox<TBuilder> method

Setzt das Attribut 'viewBox' für ein SVG-Element.

```csharp
public static TBuilder ViewBox<TBuilder>(this TBuilder builder, double minX, double minY, 
    double width, double height)
    where TBuilder : ISVGElementBuilder, IViewBoxAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| minX | Die minimale X-Koordinate des viewBox. |
| minY | Die minimale Y-Koordinate des viewBox. |
| width | Die Breite des viewBox. |
| height | Die Höhe des viewBox. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IViewBoxAttributeSetter](../../iviewboxattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
