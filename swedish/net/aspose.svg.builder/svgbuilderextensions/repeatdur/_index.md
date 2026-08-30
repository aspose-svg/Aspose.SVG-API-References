---
title: "SVGBuilderExtensions.RepeatDur"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions RepeatDur-metod. Ställer in repeatDur-attributet som specificerar den totala varaktigheten som animationen ska upprepas."
type: docs
weight: 1960
url: /sv/net/aspose.svg.builder/svgbuilderextensions/repeatdur/
---
## RepeatDur<TBuilder>(*this TBuilder, TimeSpan*) {#repeatdur_1}

Ställer in 'repeatDur'-attributet och anger den totala varaktigheten som animationen ska upprepas.

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| varaktighet | Den totala varaktigheten för att upprepa animationen. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RepeatDur<TBuilder>(*this TBuilder, [IndefiniteRepeat](../../indefiniterepeat/)*) {#repeatdur}

Ställer in 'repeatDur'-attributet och anger en obegränsad total varaktighet för animationen med en fördefinierad enum.

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, IndefiniteRepeat value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | Den fördefinierade oändliga totala varaktigheten för att upprepa animationen. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [IndefiniteRepeat](../../indefiniterepeat/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
