---
title: "SVGBuilderExtensions.KeySplines"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions KeySplines-metoden. Ställer in attributet keySplines som specificerar kontrollpunkterna för animationens tempo."
type: docs
weight: 1060
url: /sv/net/aspose.svg.builder/svgbuilderextensions/keysplines/
---
## SVGBuilderExtensions.KeySplines<TBuilder> method

Ställer in attributet 'keySplines' och specificerar kontrollpunkterna för animationens tempo.

```csharp
public static TBuilder KeySplines<TBuilder>(this TBuilder builder, 
    Action<AnimationSplineBuilder> buildSplines)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| buildSplines | Åtgärden för att bygga spline‑konfigurationen. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [AnimationSplineBuilder](../../animationsplinebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
