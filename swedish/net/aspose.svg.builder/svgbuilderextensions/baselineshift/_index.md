---
title: "SVGBuilderExtensions.BaselineShift"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions BaselineShift-metod. Ställer in baseline-shift-attributet för ett SVG-element med ett fördefinierat värde."
type: docs
weight: 600
url: /sv/net/aspose.svg.builder/svgbuilderextensions/baselineshift/
---
## BaselineShift<TBuilder>(*this TBuilder, [BaseLineShift](../../baselineshift/)*) {#baselineshift}

Ställer in attributet 'baseline-shift' för ett SVG-element med ett fördefinierat värde.

```csharp
public static TBuilder BaselineShift<TBuilder>(this TBuilder builder, BaseLineShift value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| value | Baseline-shift-värdet som ska sättas. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [BaseLineShift](../../baselineshift/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## BaselineShift<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#baselineshift_1}

Ställer in attributet 'baseline-shift' för ett SVG-element med ett numeriskt värde.

```csharp
public static TBuilder BaselineShift<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| value | Det numeriska värdet för baseline shift. |
| type | Typen av längdenhet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
