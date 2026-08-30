---
title: "SVGStyleElementBuilder.AddRule"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método AddRule de SVGStyleElementBuilder. Añade una regla CSS al elemento de estilo"
type: docs
weight: 30
url: /es/net/aspose.svg.builder/svgstyleelementbuilder/addrule/
---
## AddRule(*string, string*) {#addrule_1}

Agrega una regla CSS al elemento de estilo.

```csharp
public SVGStyleElementBuilder AddRule(string selector, string rules)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| selector | String | El selector CSS para la regla. |
| rules | String | Las reglas CSS como una cadena. |

### Valor de retorno

La instancia de SVGStyleElementBuilder para encadenamiento.

### Ver también

* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRule(*string, Action&lt;RuleBuilder&gt;*) {#addrule}

Agrega una regla CSS al elemento de estilo usando un RuleBuilder.

```csharp
public SVGStyleElementBuilder AddRule(string selector, Action<RuleBuilder> configureRule)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| selector | String | El selector CSS para la regla. |
| configureRule | Action`1 | Un delegado para configurar la regla usando un RuleBuilder. |

### Valor de retorno

La instancia de SVGStyleElementBuilder para encadenamiento.

### Ver también

* class [RuleBuilder](../../rulebuilder/)
* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
