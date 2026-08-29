---
title: "SVGBuilderExtensions.TextLength"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions TextLength-methode. Stelt de exacte lengte van de tekstinhoud in"
type: docs
weight: 2220
url: /nl/net/aspose.svg.builder/svgbuilderextensions/textlength/
---
## SVGBuilderExtensions.TextLength<TBuilder> method

Stelt de exacte lengte van de tekstinhoud in.

```csharp
public static TBuilder TextLength<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| waarde | De lengte van de tekst. |
| type | Het type lengteenheid voor de waarde. |

### Retourwaarde

De builder‑instantie voor chaining.

## Opmerkingen

Deze methode stelt het 'textLength'-attribuut in, waarmee de gewenste lengte van de tekstinhoud wordt opgegeven, mogelijk ten koste van de natuurlijke tekstlengte.

### Zie ook

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
