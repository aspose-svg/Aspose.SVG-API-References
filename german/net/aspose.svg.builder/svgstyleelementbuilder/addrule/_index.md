---
title: "SVGFEImageElementBuilder.AddRule"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGFEImageElementBuilder AddRule-Methode. Fügt dem Style-Element eine CSS-Regel hinzu."
type: docs
weight: 30
url: /de/net/aspose.svg.builder/svgstyleelementbuilder/addrule/
---
## AddRule(*string, string*) {#addrule_1}

Fügt dem Style‑Element eine CSS‑Regel hinzu.

```csharp
public SVGStyleElementBuilder AddRule(string selector, string rules)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| selector | String | Der CSS-Selektor für die Regel. |
| Regeln | String | Die CSS-Regeln als Zeichenkette. |

### Rückgabewert

Die SVGStyleElementBuilder‑Instanz für das Ketten von Aufrufen.

### Siehe auch

* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRule(*string, Action&lt;RuleBuilder&gt;*) {#addrule}

Fügt dem Style‑Element eine CSS‑Regel mithilfe eines RuleBuilders hinzu.

```csharp
public SVGStyleElementBuilder AddRule(string selector, Action<RuleBuilder> configureRule)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| selector | String | Der CSS-Selektor für die Regel. |
| configureRule | Action`1 | Ein Delegat, um die Regel mit einem RuleBuilder zu konfigurieren. |

### Rückgabewert

Die SVGStyleElementBuilder‑Instanz für das Ketten von Aufrufen.

### Siehe auch

* class [RuleBuilder](../../rulebuilder/)
* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
