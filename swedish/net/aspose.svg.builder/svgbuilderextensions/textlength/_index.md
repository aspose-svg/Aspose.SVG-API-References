---
title: "SVGBuilderExtensions.TextLength"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions TextLength-metoden. Ställer in den exakta längden på textinnehållet."
type: docs
weight: 2220
url: /sv/net/aspose.svg.builder/svgbuilderextensions/textlength/
---
## SVGBuilderExtensions.TextLength<TBuilder> method

Ställer in den exakta längden på textinnehållet.

```csharp
public static TBuilder TextLength<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | Längden på texten. |
| type | Typen av längdenhet för värdet. |

### Returvärde

Byggarinstansen för kedjning.

## Anmärkningar

Denna metod ställer in 'textLength'-attributet, vilket specificerar önskad längd på textinnehållet och eventuellt åsidosätter den naturliga textlängden.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
