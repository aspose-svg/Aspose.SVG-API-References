---
title: "SVGBuilderExtensions.Color"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions Color-methode. Stelt het kleurattribuut in voor een SVG-element met behulp van een aangepaste configuratie"
type: docs
weight: 670
url: /nl/net/aspose.svg.builder/svgbuilderextensions/color/
---
## Color<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#color}

Stelt het 'color' attribuut in voor een SVG-element met behulp van een aangepaste configuratie.

```csharp
public static TBuilder Color<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | Een delegate om de kleur te configureren. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [ColorBuilder](../../colorbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Color<TBuilder>(*this TBuilder, Color*) {#color_1}

Stelt het 'color' attribuut in voor een SVG-element met behulp van een kleurwaarde.

```csharp
public static TBuilder Color<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| colorValue | De kleurwaarde om in te stellen. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
