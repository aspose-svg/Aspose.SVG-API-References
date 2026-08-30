---
title: "SVGBuilderExtensions.WordSpacing"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions WordSpacing-metoden. Ställer in word-spacing-attributet för ett SVG-element som specificerar avståndsbeteendet mellan ord."
type: docs
weight: 2340
url: /sv/net/aspose.svg.builder/svgbuilderextensions/wordspacing/
---
## WordSpacing<TBuilder>(*this TBuilder, [Spacing](../../spacing/)*) {#wordspacing}

Ställer in attributet 'word-spacing' för ett SVG-element, som specificerar avståndsbeteendet mellan ord.

```csharp
public static TBuilder WordSpacing<TBuilder>(this TBuilder builder, Spacing value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| value | Det fördefinierade ordavståndsvärdet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [Spacing](../../spacing/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## WordSpacing<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#wordspacing_1}

Ställer in attributet 'word-spacing' för ett SVG-element, som specificerar avståndsbeteendet mellan ord med ett anpassat värde.

```csharp
public static TBuilder WordSpacing<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| value | Ordavståndsvärdet. |
| type | Enhetstypen för avståndsvärdet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
