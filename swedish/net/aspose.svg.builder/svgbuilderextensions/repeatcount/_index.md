---
title: "SVGBuilderExtensions.RepeatCount"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions RepeatCount-metoden. Ställer in repeatCount-attributet som definierar hur många gånger animationen ska upprepas."
type: docs
weight: 1950
url: /sv/net/aspose.svg.builder/svgbuilderextensions/repeatcount/
---
## RepeatCount<TBuilder>(*this TBuilder, int*) {#repeatcount_1}

Ställer in 'repeatCount'-attributet och definierar hur många gånger animationen ska upprepas.

```csharp
public static TBuilder RepeatCount<TBuilder>(this TBuilder builder, int value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | Antalet gånger animationen ska upprepas. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RepeatCount<TBuilder>(*this TBuilder, [IndefiniteRepeat](../../indefiniterepeat/)*) {#repeatcount}

Ställer in 'repeatCount'-attributet och definierar ett obegränsat repetitionsantal för animationen med en fördefinierad enum.

```csharp
public static TBuilder RepeatCount<TBuilder>(this TBuilder builder, IndefiniteRepeat value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | Det fördefinierade oändliga repetitionsantalet för animationen. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [IndefiniteRepeat](../../indefiniterepeat/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
