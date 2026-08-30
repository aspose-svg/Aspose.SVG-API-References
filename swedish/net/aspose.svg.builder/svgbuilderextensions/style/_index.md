---
title: "SVGBuilderExtensions.Style"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions Style‑metod. Ställer in style‑attributet med en regel‑byggare för att definiera CSS‑stilar"
type: docs
weight: 2160
url: /sv/net/aspose.svg.builder/svgbuilderextensions/style/
---
## Style<TBuilder>(*this TBuilder, Action&lt;RuleBuilder&gt;*) {#style}

Ställer in attributet 'style' med en regelbyggare för att definiera CSS‑stilar.

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, Action<RuleBuilder> configureRule)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| configureRule | Åtgärden för att konfigurera CSS‑regeln. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [RuleBuilder](../../rulebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Style<TBuilder>(*this TBuilder, string*) {#style_1}

Ställer in attributet 'style', vilket definierar inbäddade CSS‑stilar för SVG-elementet.

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, string rules)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| rules | CSS‑reglerna som en sträng. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
