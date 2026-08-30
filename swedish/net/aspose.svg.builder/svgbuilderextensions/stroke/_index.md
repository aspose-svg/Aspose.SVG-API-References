---
title: "SVGBuilderExtensions.Stroke"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions Stroke-metoden. Ställer in stroke-attributet för ett SVG-element med en anpassad färgkonfiguration"
type: docs
weight: 2080
url: /sv/net/aspose.svg.builder/svgbuilderextensions/stroke/
---
## Stroke<TBuilder>(*this TBuilder, Action&lt;PaintBuilder&gt;*) {#stroke_1}

Ställer in attributet 'stroke' för ett SVG-element med en anpassad målningskonfiguration.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Action<PaintBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | En delegat för att konfigurera färgen. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [PaintBuilder](../../paintbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Stroke<TBuilder>(*this TBuilder, Color*) {#stroke_2}

Ställer in attributet 'stroke' för ett SVG-element med en specifik färg.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Color color)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| färg | Färgen som ska användas för stroke. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Stroke<TBuilder>(*this TBuilder, [Paint](../../paint/)*) {#stroke}

Ställer in attributet 'stroke' för ett SVG-element med ett fördefinierat målningsvärde.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Paint paint)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| paint | Färgvärdet att ställa in. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [Paint](../../paint/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
