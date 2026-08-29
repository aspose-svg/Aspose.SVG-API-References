---
title: "SVGBuilderExtensions.Stroke"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions Stroke-methode. Stelt het stroke-attribuut in voor een SVG-element met behulp van een aangepaste schilderconfiguratie."
type: docs
weight: 2080
url: /nl/net/aspose.svg.builder/svgbuilderextensions/stroke/
---
## Stroke<TBuilder>(*this TBuilder, Action&lt;PaintBuilder&gt;*) {#stroke_1}

Stelt het 'stroke' attribuut in voor een SVG-element met behulp van een aangepaste schilderconfiguratie.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Action<PaintBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | Een delegate om de schildering te configureren. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [PaintBuilder](../../paintbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Stroke<TBuilder>(*this TBuilder, Color*) {#stroke_2}

Stelt het 'stroke' attribuut in voor een SVG-element met een specifieke kleur.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Color color)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| kleur | De kleur die voor de stroke moet worden gebruikt. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Stroke<TBuilder>(*this TBuilder, [Paint](../../paint/)*) {#stroke}

Stelt het 'stroke' attribuut in voor een SVG-element met een vooraf gedefinieerde schilderwaarde.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Paint paint)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| paint | De schilderwaarde die moet worden ingesteld. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [Paint](../../paint/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
