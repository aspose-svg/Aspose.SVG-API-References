---
title: "SVGBuilderExtensions.Height"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions Height-Methode. Legt das height-Attribut für ein SVG-Element fest."
type: docs
weight: 1000
url: /de/net/aspose.svg.builder/svgbuilderextensions/height/
---
## SVGBuilderExtensions.Height<TBuilder> method

Setzt das Attribut 'height' für ein SVG-Element.

```csharp
public static TBuilder Height<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IHeightAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| value | Der Wert für das 'height'-Attribut. |
| type | Der Typ der Längenmessung (Standard ist Pixel). |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IHeightAttributeSetter](../../iheightattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
