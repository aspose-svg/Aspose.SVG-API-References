---
title: "SVGBuilderExtensions.Dx"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions Dx-methode. Stelt het dx-attribuut in om de horizontale positie van elk teken in de tekst aan te passen."
type: docs
weight: 770
url: /nl/net/aspose.svg.builder/svgbuilderextensions/dx/
---
## Dx<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#dx}

Stelt het 'dx' attribuut in om de horizontale positie van elk teken in de tekst aan te passen.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| type | Het type lengteenheid voor de waarden. |
| waarden | De horizontale aanpassingswaarden voor elk teken. |

### Retourwaarde

De builder‑instantie voor chaining.

## Opmerkingen

Deze methode biedt fijne controle over de horizontale spatiëring van tekens in de tekst.

### Zie ook

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dx<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dx_1}

Stelt een enkele horizontale aanpassingswaarde in voor de tekstinhoud.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| waarde | De horizontale aanpassingswaarde. |
| type | Het type lengteenheid voor de waarde. |

### Retourwaarde

De builder‑instantie voor chaining.

## Opmerkingen

Deze methode stelt het 'dx'-attribuut in met een enkele waarde, waardoor de horizontale positie van de tekstinhoud wordt aangepast.

### Zie ook

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
