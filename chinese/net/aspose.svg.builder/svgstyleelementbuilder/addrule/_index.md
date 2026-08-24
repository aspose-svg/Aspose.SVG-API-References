---
title: "SVGStyleElementBuilder.AddRule"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGStyleElementBuilder AddRule 方法。向样式元素添加 CSS 规则。"
type: docs
weight: 30
url: /zh/net/aspose.svg.builder/svgstyleelementbuilder/addrule/
---
## AddRule(*string, string*) {#addrule_1}

向样式元素添加 CSS 规则。

```csharp
public SVGStyleElementBuilder AddRule(string selector, string rules)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| selector | String | 规则的 CSS 选择器。 |
| rules | String | CSS 规则的字符串形式。 |

### 返回值

用于链式调用的 SVGStyleElementBuilder 实例。

### 另请参阅

* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRule(*string, Action&lt;RuleBuilder&gt;*) {#addrule}

使用 RuleBuilder 向样式元素添加 CSS 规则。

```csharp
public SVGStyleElementBuilder AddRule(string selector, Action<RuleBuilder> configureRule)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| selector | String | 规则的 CSS 选择器。 |
| configureRule | Action`1 | 使用 RuleBuilder 配置规则的委托。 |

### 返回值

用于链式调用的 SVGStyleElementBuilder 实例。

### 另请参阅

* class [RuleBuilder](../../rulebuilder/)
* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
