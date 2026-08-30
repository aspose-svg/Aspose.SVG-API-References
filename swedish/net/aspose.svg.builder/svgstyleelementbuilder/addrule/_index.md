---
title: "SVGFEImageElementBuilder.AddRule"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGFEImageElementBuilder AddRule-metod. Lägger till en CSS-regel i stil-elementet"
type: docs
weight: 30
url: /sv/net/aspose.svg.builder/svgstyleelementbuilder/addrule/
---
## AddRule(*string, string*) {#addrule_1}

Lägger till en CSS-regel i stil-elementet.

```csharp
public SVGStyleElementBuilder AddRule(string selector, string rules)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| selector | String | CSS-väljaren för regeln. |
| rules | String | CSS‑reglerna som en sträng. |

### Returvärde

SVGStyleElementBuilder-instansen för kedjning.

### Se även

* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRule(*string, Action&lt;RuleBuilder&gt;*) {#addrule}

Lägger till en CSS-regel i stil-elementet med en RuleBuilder.

```csharp
public SVGStyleElementBuilder AddRule(string selector, Action<RuleBuilder> configureRule)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| selector | String | CSS-väljaren för regeln. |
| configureRule | Action`1 | En delegerad funktion för att konfigurera regeln med en RuleBuilder. |

### Returvärde

SVGStyleElementBuilder-instansen för kedjning.

### Se även

* class [RuleBuilder](../../rulebuilder/)
* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
