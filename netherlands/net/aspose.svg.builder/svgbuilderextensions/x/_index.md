---
title: "SVGBuilderExtensions.X"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions X-methode. Stelt het x-attribuut in voor een SVG-element"
type: docs
weight: 2360
url: /nl/net/aspose.svg.builder/svgbuilderextensions/x/
---
## X<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#x_1}

Stelt het 'x' attribuut in voor een SVG-element.

```csharp
public static TBuilder X<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IXAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| waarde | De waarde voor het 'x'-attribuut. |
| type | Het type lengtemeting (standaard is pixels). |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IXAttributeSetter](../../ixattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## X<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#x}

Stelt het 'x' attribuut in voor het positioneren van de tekstinhoud langs de x-as.

```csharp
public static TBuilder X<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| type | Het type lengteenheid voor de waarden. |
| waarden | De x-as positie‑waarden. |

### Retourwaarde

De builder‑instantie voor chaining.

## Opmerkingen

Deze methode stelt het 'x'-attribuut in, dat de horizontale positie(s) van het textelement bepaalt.

### Zie ook

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
