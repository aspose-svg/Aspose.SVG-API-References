---
title: "SVGStyleElementBuilder.AddRule"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGStyleElementBuilder AddRule yöntemi. Stil öğesine bir CSS kuralı ekler."
type: docs
weight: 30
url: /tr/net/aspose.svg.builder/svgstyleelementbuilder/addrule/
---
## AddRule(*string, string*) {#addrule_1}

Stil öğesine bir CSS kuralı ekler.

```csharp
public SVGStyleElementBuilder AddRule(string selector, string rules)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| selector | String | Kural için CSS seçicisi. |
| rules | String | CSS kuralları bir dize olarak. |

### Dönüş Değeri

Zincirleme için SVGStyleElementBuilder örneği.

### Ayrıca Bakınız

* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRule(*string, Action&lt;RuleBuilder&gt;*) {#addrule}

RuleBuilder kullanarak stil öğesine bir CSS kuralı ekler.

```csharp
public SVGStyleElementBuilder AddRule(string selector, Action<RuleBuilder> configureRule)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| selector | String | Kural için CSS seçicisi. |
| configureRule | Action`1 | Bir RuleBuilder kullanarak kuralı yapılandırmak için bir temsilci. |

### Dönüş Değeri

Zincirleme için SVGStyleElementBuilder örneği.

### Ayrıca Bakınız

* class [RuleBuilder](../../rulebuilder/)
* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
