---
title: "SVGStyleElementBuilder.AddRule"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo AddRule di SVGStyleElementBuilder. Aggiunge una regola CSS all'elemento style"
type: docs
weight: 30
url: /it/net/aspose.svg.builder/svgstyleelementbuilder/addrule/
---
## AddRule(*string, string*) {#addrule_1}

Aggiunge una regola CSS all'elemento di stile.

```csharp
public SVGStyleElementBuilder AddRule(string selector, string rules)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| selector | String | Il selettore CSS per la regola. |
| rules | String | Le regole CSS come stringa. |

### Valore di ritorno

L'istanza di SVGStyleElementBuilder per il chaining.

### Vedi anche

* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRule(*string, Action&lt;RuleBuilder&gt;*) {#addrule}

Aggiunge una regola CSS all'elemento di stile utilizzando un RuleBuilder.

```csharp
public SVGStyleElementBuilder AddRule(string selector, Action<RuleBuilder> configureRule)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| selector | String | Il selettore CSS per la regola. |
| configureRule | Action`1 | Un delegato per configurare la regola usando un RuleBuilder. |

### Valore di ritorno

L'istanza di SVGStyleElementBuilder per il chaining.

### Vedi anche

* class [RuleBuilder](../../rulebuilder/)
* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
