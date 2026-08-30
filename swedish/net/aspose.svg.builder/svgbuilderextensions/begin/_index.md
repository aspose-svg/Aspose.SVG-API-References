---
title: "SVGBuilderExtensions.Begin"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions Begin‑metod. Ställer in begin‑attributet som definierar när animationen ska starta."
type: docs
weight: 610
url: /sv/net/aspose.svg.builder/svgbuilderextensions/begin/
---
## SVGBuilderExtensions.Begin<TBuilder> method

Ställer in attributet 'begin', som definierar när animationen ska starta.

```csharp
public static TBuilder Begin<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
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
