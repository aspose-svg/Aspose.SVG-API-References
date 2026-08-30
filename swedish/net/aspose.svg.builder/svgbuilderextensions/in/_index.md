---
title: "SVGBuilderExtensions.In"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions In-metoden. Ställer in in-attributet för en SVG-filterprimitive"
type: docs
weight: 1040
url: /sv/net/aspose.svg.builder/svgbuilderextensions/in/
---
## In<TBuilder>(*this TBuilder, string*) {#in_1}

Ställer in attributet 'in' för en SVG-filterprimitive.

```csharp
public static TBuilder In<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveInAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| value | Källgrafiken eller filterprimitivresultatet som ska användas som indata. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../../ifilterprimitiveinattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## In<TBuilder>(*this TBuilder, [FilterInput](../../filterinput/)*) {#in}

Ställer in attributet 'in' för en SVG-filterprimitive med en fördefinierad inmatningskälla.

```csharp
public static TBuilder In<TBuilder>(this TBuilder builder, FilterInput input)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveInAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| input | Den fördefinierade indata-källan (t.ex. SourceGraphic, SourceAlpha). |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [FilterInput](../../filterinput/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../../ifilterprimitiveinattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
