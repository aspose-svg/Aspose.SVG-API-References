---
title: "SVGBuilderExtensions.Style"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions Style-methode. Stelt het style-attribuut in met behulp van een regel‑bouwer om CSS‑stijlen te definiëren."
type: docs
weight: 2160
url: /nl/net/aspose.svg.builder/svgbuilderextensions/style/
---
## Style<TBuilder>(*this TBuilder, Action&lt;RuleBuilder&gt;*) {#style}

Stelt het 'style' attribuut in met behulp van een regelbouwer om CSS-stijlen te definiëren.

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, Action<RuleBuilder> configureRule)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| configureRule | De actie om de CSS-regel te configureren. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [RuleBuilder](../../rulebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Style<TBuilder>(*this TBuilder, string*) {#style_1}

Stelt het 'style' attribuut in, waarbij inline CSS-stijlen voor het SVG-element worden gedefinieerd.

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, string rules)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| rules | De CSS-regels als een tekenreeks. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
