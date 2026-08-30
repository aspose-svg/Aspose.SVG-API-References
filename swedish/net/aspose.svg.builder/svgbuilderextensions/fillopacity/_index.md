---
title: "SVGBuilderExtensions.FillOpacity"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions FillOpacity‑metoden. Ställer in fill-opacity‑attributet för ett SVG‑element. Värdet måste vara mellan 0,0 helt transparent och 1,0 helt ogenomskinligt."
type: docs
weight: 820
url: /sv/net/aspose.svg.builder/svgbuilderextensions/fillopacity/
---
## SVGBuilderExtensions.FillOpacity<TBuilder> method

Ställer in attributet 'fill-opacity' för ett SVG-element. Värdet måste vara mellan 0.0 (fullt genomskinligt) och 1.0 (fullt ogenomskinligt).

```csharp
public static TBuilder FillOpacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| opacity | Opacitetsvärdet att sätta. |

### Returvärde

Byggarinstansen för kedjning.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | Kastas om opaciteten inte är inom giltigt intervall. |

### Se även

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
