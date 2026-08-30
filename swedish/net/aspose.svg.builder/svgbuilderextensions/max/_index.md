---
title: "SVGBuilderExtensions.Max"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions Max-metoden. Ställer in max-attributet som specificerar den maximala varaktigheten för animationen."
type: docs
weight: 1160
url: /sv/net/aspose.svg.builder/svgbuilderextensions/max/
---
## Max<TBuilder>(*this TBuilder, TimeSpan*) {#max_1}

Ställer in attributet 'max' och anger den maximala varaktigheten för animationen.

```csharp
public static TBuilder Max<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| varaktighet | Den maximala varaktigheten för animationen. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Max<TBuilder>(*this TBuilder, [Media](../../media/)*) {#max}

Ställer in attributet 'max' och anger det fördefinierade maximala varaktighetsvillkoret för animationen.

```csharp
public static TBuilder Max<TBuilder>(this TBuilder builder, Media value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | Det fördefinierade maximala varaktighetsvillkoret för animationen. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [Media](../../media/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
