---
title: "SVGBuilderExtensions.In"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions In methode. Stelt het in‑attribuut in voor een SVG-filter‑primitive."
type: docs
weight: 1040
url: /nl/net/aspose.svg.builder/svgbuilderextensions/in/
---
## In<TBuilder>(*this TBuilder, string*) {#in_1}

Stelt het 'in' attribuut in voor een SVG-filterprimitive.

```csharp
public static TBuilder In<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveInAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| waarde | De bron‑grafiek of filter‑primitive‑resultaat om te gebruiken als invoer. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../../ifilterprimitiveinattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## In<TBuilder>(*this TBuilder, [FilterInput](../../filterinput/)*) {#in}

Stelt het 'in' attribuut voor een SVG-filterprimitive in met een vooraf gedefinieerde invoerbron.

```csharp
public static TBuilder In<TBuilder>(this TBuilder builder, FilterInput input)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveInAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| invoer | De vooraf gedefinieerde invoerbron (bijv. SourceGraphic, SourceAlpha). |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [FilterInput](../../filterinput/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../../ifilterprimitiveinattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
