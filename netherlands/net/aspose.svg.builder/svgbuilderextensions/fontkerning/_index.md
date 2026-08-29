---
title: "SVGBuilderExtensions.FontKerning"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions FontKerning‑methode. Stelt het font-kerning‑attribuut in voor een SVG‑element met een numerieke waarde en een specifiek length type"
type: docs
weight: 880
url: /nl/net/aspose.svg.builder/svgbuilderextensions/fontkerning/
---
## FontKerning<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#fontkerning_1}

Stelt het 'font-kerning' attribuut voor een SVG-element in met een numerieke waarde en een specifiek lengtetype.

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| waarde | De font‑kerning‑waarde die moet worden ingesteld. |
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

## FontKerning<TBuilder>(*this TBuilder, [Kerning](../../kerning/)*) {#fontkerning}

Stelt het 'font-kerning' attribuut voor een SVG-element in met een vooraf gedefinieerde kerningwaarde.

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, Kerning value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| waarde | De vooraf gedefinieerde kerning‑waarde die moet worden ingesteld. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [Kerning](../../kerning/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
