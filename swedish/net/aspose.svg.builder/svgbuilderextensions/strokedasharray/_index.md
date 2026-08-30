---
title: "SVGBuilderExtensions.StrokeDashArray"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions StrokeDashArray-metoden. Ställer in stroke-dasharray‑attributet för ett SVG‑element som definierar mönstret av streck och mellanrum som används för att måla linjen"
type: docs
weight: 2090
url: /sv/net/aspose.svg.builder/svgbuilderextensions/strokedasharray/
---
## StrokeDashArray<TBuilder>(*this TBuilder, params double[]*) {#strokedasharray_1}

Ställer in attributet 'stroke-dasharray' för ett SVG-element, vilket definierar mönstret av streck och mellanrum som används för att måla linjen.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, params double[] dashArray)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| dashArray | Arrayen med dash‑längder. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## StrokeDashArray<TBuilder>(*this TBuilder, [Dash](../../dash/)*) {#strokedasharray}

Ställer in attributet 'stroke-dasharray' för ett SVG-element med ett fördefinierat streckmönster.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, Dash value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| value | Dash‑mönstret att sätta. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [Dash](../../dash/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
