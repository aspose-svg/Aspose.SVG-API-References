---
title: "SVGBuilderExtensions.Points"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions Points-metoden. Ställer in points-attributet för ett SVG-element med en array av double-värden."
type: docs
weight: 1910
url: /sv/net/aspose.svg.builder/svgbuilderextensions/points/
---
## Points<TBuilder>(*this TBuilder, params double[]*) {#points}

Ställer in 'points'-attributet för ett SVG-element med en array av dubbla värden.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params double[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| points | En array av double-värden som representerar punkterna (måste vara ett jämnt antal). |

### Returvärde

Byggarinstansen för kedjning.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om ett udda antal punkter tillhandahålls. |

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Points<TBuilder>(*this TBuilder, params PointF[]*) {#points_1}

Ställer in 'points'-attributet för ett SVG-element med en array av PointF‑objekt.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params PointF[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| points | En array av PointF-objekt som representerar punkterna. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
