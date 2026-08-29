---
title: "SVGBuilderExtensions.FloodColor"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions FloodColor methode. Stelt het flood-color‑attribuut in voor een SVG-element met behulp van een System.Drawing-kleur"
type: docs
weight: 850
url: /nl/net/aspose.svg.builder/svgbuilderextensions/floodcolor/
---
## FloodColor<TBuilder>(*this TBuilder, Color*) {#floodcolor_1}

Stelt het 'flood-color' attribuut voor een SVG-element in met een System.Drawing-kleur.

```csharp
public static TBuilder FloodColor<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| colorValue | De kleur die als flood-kleur moet worden ingesteld. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## FloodColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#floodcolor}

Stelt het 'flood-color' attribuut voor een SVG-element in met een aangepaste kleurenconfiguratie.

```csharp
public static TBuilder FloodColor<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | Een delegate om de ColorBuilder te configureren. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [ColorBuilder](../../colorbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
