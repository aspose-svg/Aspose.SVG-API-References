---
title: "SVGBuilderExtensions.StrokeDashArray"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions StrokeDashArray-methode. Stelt het stroke-dasharray‑attribuut in voor een SVG‑element dat het patroon van streepjes en gaten definieert dat wordt gebruikt om de lijn te schilderen."
type: docs
weight: 2090
url: /nl/net/aspose.svg.builder/svgbuilderextensions/strokedasharray/
---
## StrokeDashArray<TBuilder>(*this TBuilder, params double[]*) {#strokedasharray_1}

Stelt het 'stroke-dasharray' attribuut in voor een SVG-element, waarbij het patroon van strepen en onderbrekingen dat wordt gebruikt om de lijn te schilderen wordt gedefinieerd.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, params double[] dashArray)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| dashArray | The array met dashlengtes. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## StrokeDashArray<TBuilder>(*this TBuilder, [Dash](../../dash/)*) {#strokedasharray}

Stelt het 'stroke-dasharray' attribuut in voor een SVG-element met een vooraf gedefinieerd streepjespatroon.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, Dash value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| waarde | Het dash-patroon om in te stellen. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [Dash](../../dash/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
