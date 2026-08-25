---
title: "SVGStyleElementBuilder.AddRule"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode AddRule de SVGStyleElementBuilder. Ajoute une règle CSS à l'élément de style"
type: docs
weight: 30
url: /fr/net/aspose.svg.builder/svgstyleelementbuilder/addrule/
---
## AddRule(*string, string*) {#addrule_1}

Ajoute une règle CSS à l'élément de style.

```csharp
public SVGStyleElementBuilder AddRule(string selector, string rules)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| selector | String | Le sélecteur CSS pour la règle. |
| rules | String | Les règles CSS sous forme de chaîne. |

### Valeur de retour

L'instance de SVGStyleElementBuilder pour le chaînage.

### Voir aussi

* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRule(*string, Action&lt;RuleBuilder&gt;*) {#addrule}

Ajoute une règle CSS à l'élément de style en utilisant un RuleBuilder.

```csharp
public SVGStyleElementBuilder AddRule(string selector, Action<RuleBuilder> configureRule)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| selector | String | Le sélecteur CSS pour la règle. |
| configureRule | Action`1 | Un délégué pour configurer la règle en utilisant un RuleBuilder. |

### Valeur de retour

L'instance de SVGStyleElementBuilder pour le chaînage.

### Voir aussi

* class [RuleBuilder](../../rulebuilder/)
* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
