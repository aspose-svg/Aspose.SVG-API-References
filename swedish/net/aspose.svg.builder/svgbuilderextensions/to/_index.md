---
title: "SVGBuilderExtensions.To"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions To-metoden. Ställer in to-attributet som definierar slutvärdet för animationen med en angiven längdtyp."
type: docs
weight: 2250
url: /sv/net/aspose.svg.builder/svgbuilderextensions/to/
---
## SVGBuilderExtensions.To<TBuilder> method

Ställer in attributet 'to', som definierar slutvärdet för animationen med en angiven längdtyp.

```csharp
public static TBuilder To<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | Det avslutande värdet för animationen. |
| type | Längdtypen för 'to'-värdet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
