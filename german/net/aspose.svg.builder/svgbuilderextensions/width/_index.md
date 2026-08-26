---
title: "SVGBuilderExtensions.Width"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions Width Methode. Setzt das width-Attribut für ein SVG-Element."
type: docs
weight: 2330
url: /de/net/aspose.svg.builder/svgbuilderextensions/width/
---
## SVGBuilderExtensions.Width<TBuilder> method

Setzt das Attribut 'width' für ein SVG-Element.

```csharp
public static TBuilder Width<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IWidthAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| value | Der Wert für das 'width'-Attribut. |
| type | Der Typ der Längenmessung (Standard ist Pixel). |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IWidthAttributeSetter](../../iwidthattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
