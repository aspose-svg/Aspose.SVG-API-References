---
title: "SVGBuilderExtensions.LightingColor"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions LightingColor-methode. Stelt het lighting-color‑attribuut in voor een SVG-element met een opgegeven kleurwaarde"
type: docs
weight: 1110
url: /nl/net/aspose.svg.builder/svgbuilderextensions/lightingcolor/
---
## LightingColor<TBuilder>(*this TBuilder, Color*) {#lightingcolor_1}

Stelt het 'lighting-color' attribuut in voor een SVG-element met een opgegeven kleurwaarde.

```csharp
public static TBuilder LightingColor<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| colorValue | De kleurwaarde die moet worden ingesteld voor het lichteffect. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## LightingColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#lightingcolor}

Stelt het 'lighting-color' attribuut in voor een SVG-element met een aangepaste kleurconfiguratie.

```csharp
public static TBuilder LightingColor<TBuilder>(this TBuilder builder, 
    Action<ColorBuilder> configure)
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
