---
title: "SVGBuilderExtensions.From"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions From-metoden. Ställer in from-attributet som definierar startvärdet för animationen med en angiven längdtyp"
type: docs
weight: 960
url: /sv/net/aspose.svg.builder/svgbuilderextensions/from/
---
## SVGBuilderExtensions.From<TBuilder> method

Ställer in attributet 'from', som definierar startvärdet för animationen med en angiven längdtyp.

```csharp
public static TBuilder From<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | Startvärdet för animationen. |
| type | Längdtypen för 'from'-värdet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
