---
title: "SVGStyleElementBuilder.AddRule"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGStyleElementBuilder AddRule-methode. Voegt een CSS-regel toe aan het stijlelement."
type: docs
weight: 30
url: /nl/net/aspose.svg.builder/svgstyleelementbuilder/addrule/
---
## AddRule(*string, string*) {#addrule_1}

Voegt een CSS-regel toe aan het style-element.

```csharp
public SVGStyleElementBuilder AddRule(string selector, string rules)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| selector | String | De CSS-selector voor de regel. |
| rules | String | De CSS-regels als een tekenreeks. |

### Retourwaarde

De SVGStyleElementBuilder-instantie voor chaining.

### Zie ook

* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRule(*string, Action&lt;RuleBuilder&gt;*) {#addrule}

Voegt een CSS-regel toe aan het style-element met behulp van een RuleBuilder.

```csharp
public SVGStyleElementBuilder AddRule(string selector, Action<RuleBuilder> configureRule)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| selector | String | De CSS-selector voor de regel. |
| configureRule | Action`1 | Een delegate om de regel te configureren met een RuleBuilder. |

### Retourwaarde

De SVGStyleElementBuilder-instantie voor chaining.

### Zie ook

* class [RuleBuilder](../../rulebuilder/)
* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
