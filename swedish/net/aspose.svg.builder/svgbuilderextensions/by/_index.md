---
title: "SVGBuilderExtensions.By"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions By-metoden. Ställer in by-attributet som definierar det relativa förskjutningsvärdet för animationen med en angiven längdtyp."
type: docs
weight: 620
url: /sv/net/aspose.svg.builder/svgbuilderextensions/by/
---
## SVGBuilderExtensions.By<TBuilder> method

Ställer in attributet 'by', som definierar det relativa förskjutningsvärdet för animationen med en specificerad längdtyp.

```csharp
public static TBuilder By<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | Det relativa förskjutningsvärdet för animationen. |
| type | Längdtypen för 'by'-värdet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
