---
title: "SVGBuilderExtensions.Rotate"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions Rotate-metod. Ställer in rotationsvinklar för enskilda tecken eller segment av textinnehållet."
type: docs
weight: 2000
url: /sv/net/aspose.svg.builder/svgbuilderextensions/rotate/
---
## Rotate<TBuilder>(*this TBuilder, params double[]*) {#rotate_1}

Ställer in rotationsvinklar för enskilda tecken eller segment av textinnehållet.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| values | En array av rotationsvinklar i grader. |

### Returvärde

Byggarinstansen för kedjning.

## Anmärkningar

Denna metod ställer in 'rotate'-attributet med flera värden, vilket möjliggör individuell rotation av varje tecken eller textsegment.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Rotate<TBuilder>(*this TBuilder, double*) {#rotate}

Ställer in en enda rotationsvinkel för hela textinnehållet.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, double value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | Rotationsvinkeln i grader. |

### Returvärde

Byggarinstansen för kedjning.

## Anmärkningar

Denna metod ställer in 'rotate'-attributet med ett enda värde, vilket applicerar samma rotationsvinkel på allt textinnehåll.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
