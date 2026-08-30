---
title: "SVGBuilderExtensions.LetterSpacing"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions LetterSpacing-metod. Ställer in letter-spacing-attributet för ett SVG-element med ett numeriskt värde och en specifik längdtyp"
type: docs
weight: 1100
url: /sv/net/aspose.svg.builder/svgbuilderextensions/letterspacing/
---
## LetterSpacing<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#letterspacing_1}

Ställer in attributet 'letter-spacing' för ett SVG-element med ett numeriskt värde och en specifik längdtyp.

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| value | Letter-spacing‑värdet att sätta. |
| type | Längdtypen (t.ex. px, em). |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## LetterSpacing<TBuilder>(*this TBuilder, [Spacing](../../spacing/)*) {#letterspacing}

Ställer in attributet 'letter-spacing' för ett SVG-element med ett fördefinierat avståndsvärde.

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, Spacing value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| value | Det fördefinierade avståndsvärdet att sätta. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [Spacing](../../spacing/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
