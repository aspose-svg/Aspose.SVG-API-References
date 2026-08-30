---
title: "SVGBuilderExtensions.Values"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions Values-metoden. Ställer in values‑attributet som specificerar mängden värden som ska användas under animationen"
type: docs
weight: 2290
url: /sv/net/aspose.svg.builder/svgbuilderextensions/values/
---
## SVGBuilderExtensions.Values<TBuilder> method

Ställer in attributet 'values', som specificerar mängden värden som ska användas under animationens gång.

```csharp
public static TBuilder Values<TBuilder>(this TBuilder builder, params string[] values)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| values | Arrayen med värden för animationen. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
