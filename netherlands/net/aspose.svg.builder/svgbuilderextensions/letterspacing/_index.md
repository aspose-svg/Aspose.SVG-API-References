---
title: "SVGBuilderExtensions.LetterSpacing"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions LetterSpacing-methode. Stelt het letter-spacing attribuut in voor een SVG-element met een numerieke waarde en een specifiek lengtetype."
type: docs
weight: 1100
url: /nl/net/aspose.svg.builder/svgbuilderextensions/letterspacing/
---
## LetterSpacing<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#letterspacing_1}

Stelt het 'letter-spacing' attribuut in voor een SVG-element met een numerieke waarde en een specifiek lengtype.

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| waarde | De letter-spacing waarde die moet worden ingesteld. |
| type | Het length type (bijv. px, em). |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## LetterSpacing<TBuilder>(*this TBuilder, [Spacing](../../spacing/)*) {#letterspacing}

Stelt het 'letter-spacing' attribuut in voor een SVG-element met een vooraf gedefinieerde spatiëringswaarde.

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, Spacing value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| waarde | De vooraf gedefinieerde spacing-waarde die moet worden ingesteld. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [Spacing](../../spacing/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
