---
title: "SVGBuilderExtensions.RefY"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions RefY-methode. Stelt het refY-attribuut in voor een SVG-element"
type: docs
weight: 1940
url: /nl/net/aspose.svg.builder/svgbuilderextensions/refy/
---
## RefY<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#refy_1}

Stelt het 'refY' attribuut in voor een SVG-element.

```csharp
public static TBuilder RefY<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRefCoordinatesAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| waarde | De referentie-Y-coördinaat. |
| type | Het type lengteenheid (standaard is pixels). |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRefCoordinatesAttributeSetter](../../irefcoordinatesattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RefY<TBuilder>(*this TBuilder, [VerticalPosition](../../verticalposition/)*) {#refy}

Stelt het 'refY'‑attribuut in voor een SVG‑element met een vooraf gedefinieerde verticale positie.

```csharp
public static TBuilder RefY<TBuilder>(this TBuilder builder, VerticalPosition value)
    where TBuilder : ISVGElementBuilder, IRefCoordinatesAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| waarde | De vooraf gedefinieerde verticale positie. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [VerticalPosition](../../verticalposition/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRefCoordinatesAttributeSetter](../../irefcoordinatesattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
