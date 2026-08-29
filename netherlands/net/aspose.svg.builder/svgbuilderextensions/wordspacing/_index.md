---
title: "SVGBuilderExtensions.WordSpacing"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions WordSpacing-methode. Stelt het word-spacing-attribuut in voor een SVG-element dat het spatiëringsgedrag tussen woorden specificeert."
type: docs
weight: 2340
url: /nl/net/aspose.svg.builder/svgbuilderextensions/wordspacing/
---
## WordSpacing<TBuilder>(*this TBuilder, [Spacing](../../spacing/)*) {#wordspacing}

Stelt het 'word-spacing' attribuut in voor een SVG-element, waarbij het spatiëringsgedrag tussen woorden wordt gespecificeerd.

```csharp
public static TBuilder WordSpacing<TBuilder>(this TBuilder builder, Spacing value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| waarde | De vooraf gedefinieerde woord-spatiëringswaarde. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [Spacing](../../spacing/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## WordSpacing<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#wordspacing_1}

Stelt het 'word-spacing' attribuut in voor een SVG-element, waarbij het spatiëringsgedrag tussen woorden met een aangepaste waarde wordt gespecificeerd.

```csharp
public static TBuilder WordSpacing<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| waarde | De woord-spatiëringswaarde. |
| type | Het eenheidstype voor de spatiëringswaarde. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
