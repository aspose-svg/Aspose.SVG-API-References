---
title: "SVGStyleElementBuilder.AddRule"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGStyleElementBuilder AddRule. تضيف قاعدة CSS إلى عنصر النمط."
type: docs
weight: 30
url: /ar/net/aspose.svg.builder/svgstyleelementbuilder/addrule/
---
## AddRule(*string, string*) {#addrule_1}

يضيف قاعدة CSS إلى عنصر النمط.

```csharp
public SVGStyleElementBuilder AddRule(string selector, string rules)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| selector | String | المحدد CSS للقاعدة. |
| rules | String | قواعد CSS كسلسلة نصية. |

### قيمة الإرجاع

مثيل SVGStyleElementBuilder للتسلسل.

### انظر أيضًا

* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRule(*string, Action&lt;RuleBuilder&gt;*) {#addrule}

يضيف قاعدة CSS إلى عنصر النمط باستخدام RuleBuilder.

```csharp
public SVGStyleElementBuilder AddRule(string selector, Action<RuleBuilder> configureRule)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| selector | String | المحدد CSS للقاعدة. |
| configureRule | Action`1 | مفوض لتكوين القاعدة باستخدام RuleBuilder. |

### قيمة الإرجاع

مثيل SVGStyleElementBuilder للتسلسل.

### انظر أيضًا

* class [RuleBuilder](../../rulebuilder/)
* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
