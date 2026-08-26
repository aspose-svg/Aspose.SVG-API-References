---
title: "SVGBuilderExtensions.Style"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions Style‑Methode. Setzt das style‑Attribut mithilfe eines Regel‑Builders, um CSS‑Stile zu definieren."
type: docs
weight: 2160
url: /de/net/aspose.svg.builder/svgbuilderextensions/style/
---
## Style<TBuilder>(*this TBuilder, Action&lt;RuleBuilder&gt;*) {#style}

Setzt das Attribut 'style' mithilfe eines Regelgenerators, um CSS-Stile zu definieren.

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, Action<RuleBuilder> configureRule)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| configureRule | Die Aktion zum Konfigurieren der CSS-Regel. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [RuleBuilder](../../rulebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Style<TBuilder>(*this TBuilder, string*) {#style_1}

Setzt das Attribut 'style' und definiert Inline-CSS-Stile für das SVG-Element.

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, string rules)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| Regeln | Die CSS-Regeln als Zeichenkette. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
