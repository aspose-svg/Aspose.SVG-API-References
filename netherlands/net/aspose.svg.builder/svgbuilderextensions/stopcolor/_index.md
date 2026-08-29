---
title: "SVGBuilderExtensions.StopColor"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions StopColor-methode. Stelt het stop-color‑attribuut in voor een SVG-element dat de kleur bij een kleurverloopstop definieert"
type: docs
weight: 2060
url: /nl/net/aspose.svg.builder/svgbuilderextensions/stopcolor/
---
## StopColor<TBuilder>(*this TBuilder, Color*) {#stopcolor_1}

Stelt het 'stop-color' attribuut in voor een SVG-element, waarbij de kleur bij een gradient‑stop wordt gedefinieerd.

```csharp
public static TBuilder StopColor<TBuilder>(this TBuilder builder, Color colorValue)
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

---

## StopColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#stopcolor}

Stelt het 'stop-color' attribuut in voor een SVG-element met behulp van een aangepaste kleurconfiguratie.

```csharp
public static TBuilder StopColor<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
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
