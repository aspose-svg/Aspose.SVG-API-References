---
title: "SVGBuilderExtensions.Dx"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions Dx-metod. Ställer in dx-attributet för att justera den horisontella positionen för varje tecken i texten"
type: docs
weight: 770
url: /sv/net/aspose.svg.builder/svgbuilderextensions/dx/
---
## Dx<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#dx}

Ställer in attributet 'dx' för att justera den horisontella positionen för varje tecken i texten.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| type | Typen av längdenhet för värdena. |
| values | De horisontella justeringsvärdena för varje tecken. |

### Returvärde

Byggarinstansen för kedjning.

## Anmärkningar

Denna metod möjliggör fin kontroll över horisontellt avstånd mellan tecken i texten.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dx<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dx_1}

Ställer in ett enda horisontellt justeringsvärde för textinnehållet.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | Det horisontella justeringsvärdet. |
| type | Typen av längdenhet för värdet. |

### Returvärde

Byggarinstansen för kedjning.

## Anmärkningar

Denna metod sätter 'dx'-attributet med ett enda värde och justerar den horisontella positionen för textinnehållet.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
