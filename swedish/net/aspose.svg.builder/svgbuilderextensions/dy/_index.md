---
title: "SVGBuilderExtensions.Dy"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions Dy-metoden. Ställer in flera vertikala justeringsvärden för textinnehållet"
type: docs
weight: 780
url: /sv/net/aspose.svg.builder/svgbuilderextensions/dy/
---
## Dy<TBuilder>(*this TBuilder, double[], [LengthType](../../lengthtype/)*) {#dy_1}

Ställer in flera vertikala justeringsvärden för textinnehållet.

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double[] values, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| values | Arrayen med vertikala justeringsvärden. |
| type | Typen av längdenhet för värdena. |

### Returvärde

Byggarinstansen för kedjning.

## Anmärkningar

Denna metod sätter 'dy'-attributet med flera värden, vilket möjliggör individuella vertikala justeringar för varje tecken eller textsegment.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dy<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dy}

Ställer in ett enda vertikalt justeringsvärde för textinnehållet.

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | Det vertikala justeringsvärdet. |
| type | Typen av längdenhet för värdet. |

### Returvärde

Byggarinstansen för kedjning.

## Anmärkningar

Denna metod sätter 'dy'-attributet med ett enda värde och justerar den vertikala positionen för textinnehållet.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
