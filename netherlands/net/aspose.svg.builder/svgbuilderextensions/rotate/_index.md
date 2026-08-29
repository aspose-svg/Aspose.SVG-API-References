---
title: "SVGBuilderExtensions.Rotate"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions Rotate-methode. Stelt rotatiehoeken in voor individuele tekens of segmenten van de tekstinhoud"
type: docs
weight: 2000
url: /nl/net/aspose.svg.builder/svgbuilderextensions/rotate/
---
## Rotate<TBuilder>(*this TBuilder, params double[]*) {#rotate_1}

Stelt rotatiehoeken in voor individuele tekens of segmenten van de tekstinhoud.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| waarden | Een array van rotatiehoeken in graden. |

### Retourwaarde

De builder‑instantie voor chaining.

## Opmerkingen

Deze methode stelt het 'rotate'-attribuut in met meerdere waarden, waardoor individuele rotatie van elk teken of tekstsegment mogelijk is.

### Zie ook

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Rotate<TBuilder>(*this TBuilder, double*) {#rotate}

Stelt een enkele rotatiehoek in voor de volledige tekstinhoud.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, double value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| waarde | De rotatiehoek in graden. |

### Retourwaarde

De builder‑instantie voor chaining.

## Opmerkingen

Deze methode stelt het 'rotate'-attribuut in met één waarde, waardoor dezelfde rotatiehoek op alle tekstinhoud wordt toegepast.

### Zie ook

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
