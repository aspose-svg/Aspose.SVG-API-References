---
title: "SVGBuilderExtensions.Dur"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions Dur-metod. Anger dur‑attributet som specificerar animationens varaktighet"
type: docs
weight: 760
url: /sv/net/aspose.svg.builder/svgbuilderextensions/dur/
---
## Dur<TBuilder>(*this TBuilder, TimeSpan*) {#dur_1}

Ställer in attributet 'dur' och anger varaktigheten för animationen.

```csharp
public static TBuilder Dur<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| varaktighet | Animationens varaktighet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dur<TBuilder>(*this TBuilder, [Dur](../../dur/)*) {#dur}

Ställer in attributet 'dur' och anger den fördefinierade varaktighetstypen för animationen.

```csharp
public static TBuilder Dur<TBuilder>(this TBuilder builder, Dur value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | Den fördefinierade varaktighetstypen för animationen. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [Dur](../../dur/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
