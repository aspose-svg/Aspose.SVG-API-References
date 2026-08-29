---
title: "SVGBuilderExtensions.Dy"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions Dy-methode. Stelt meerdere verticale aanpassingswaarden in voor de tekstinhoud"
type: docs
weight: 780
url: /nl/net/aspose.svg.builder/svgbuilderextensions/dy/
---
## Dy<TBuilder>(*this TBuilder, double[], [LengthType](../../lengthtype/)*) {#dy_1}

Stelt meerdere verticale aanpassingswaarden in voor de tekstinhoud.

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double[] values, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| waarden | De array met verticale aanpassingswaarden. |
| type | Het type lengteenheid voor de waarden. |

### Retourwaarde

De builder‑instantie voor chaining.

## Opmerkingen

Deze methode stelt het 'dy'-attribuut in met meerdere waarden, waardoor individuele verticale aanpassingen voor elk teken of tekstsegment mogelijk zijn.

### Zie ook

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dy<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dy}

Stelt een enkele verticale aanpassingswaarde in voor de tekstinhoud.

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| waarde | De verticale aanpassingswaarde. |
| type | Het type lengteenheid voor de waarde. |

### Retourwaarde

De builder‑instantie voor chaining.

## Opmerkingen

Deze methode stelt het 'dy'-attribuut in met één waarde, waardoor de verticale positie van de tekstinhoud wordt aangepast.

### Zie ook

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
