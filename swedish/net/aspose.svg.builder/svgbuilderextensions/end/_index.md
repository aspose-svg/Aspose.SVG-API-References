---
title: "SVGBuilderExtensions.End"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions End-metoden. Ställer in end-attributet som definierar när animationen ska sluta"
type: docs
weight: 790
url: /sv/net/aspose.svg.builder/svgbuilderextensions/end/
---
## SVGBuilderExtensions.End<TBuilder> method

Ställer in attributet 'end' och definierar när animationen ska avslutas.

```csharp
public static TBuilder End<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| konfigurera | En delegat för att konfigurera tidsvärdet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [TimingValueBuilder](../../timingvaluebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
