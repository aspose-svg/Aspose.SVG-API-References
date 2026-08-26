---
title: "SVGBuilderExtensions.TextLength"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions TextLength-Methode. Legt die genaue Länge des Textinhalts fest"
type: docs
weight: 2220
url: /de/net/aspose.svg.builder/svgbuilderextensions/textlength/
---
## SVGBuilderExtensions.TextLength<TBuilder> method

Setzt die genaue Länge des Textinhalts.

```csharp
public static TBuilder TextLength<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Die Länge des Textes. |
| type | Der Typ der Längeneinheit für den Wert. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

## Hinweise

Diese Methode setzt das Attribut 'textLength' und gibt die gewünschte Länge des Textinhalts an, wobei ggf. die natürliche Textlänge überschrieben wird.

### Siehe auch

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
