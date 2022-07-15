---
title: CreateExpression
second_title: Aspose.SVG for .NET API 参考
description: 使用已解析的命名空间创建已解析的 XPath 表达式当表达式将在应用程序中重用时这很有用 因为它可以使 将表达式字符串编译成更有效的内部形式并且 可以预解析所有出现的命名空间前缀表达式内
type: docs
weight: 10
url: /zh/net/aspose.svg.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

使用已解析的命名空间创建已解析的 XPath 表达式。当表达式将在应用程序中重用时，这很有用 ，因为它可以使 将表达式字符串编译成更有效的内部形式，并且 可以预解析所有出现的命名空间前缀表达式内。

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| expression | String | 要解析的 XPath 表达式字符串。 |
| resolver | IXPathNSResolver | ` 解析器` 允许翻译所有前缀， 包括` xml` 命名空间前缀，在 XPath 表达式内转换成 适当的命名空间 URI。如果指定为` null` ，则表达式中的任何命名空间 前缀都将导致[`DOMException`](../../../aspose.svg.dom/domexception)为 与代码` NAMESPACE_ERR` 一起抛出。 |

### 返回值

XPath 表达式的编译形式。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception) | INVALID_EXPRESSION_ERR：根据 的规则，如果表达式不是 合法，则引发。 [`IXPathEvaluator`](../../ixpathevaluator)。 |
| [DOMException](../../../aspose.svg.dom/domexception) | NAMESPACE_ERR：如果表达式包含命名空间 前缀，而不能被指定的解析，则引发[`IXPathNSResolver`](../../ixpathnsresolver)。 |

### 也可以看看

* interface [IXPathExpression](../../ixpathexpression)
* interface [IXPathNSResolver](../../ixpathnsresolver)
* interface [IXPathEvaluator](../../ixpathevaluator)
* 命名空间 [Aspose.Svg.Dom.XPath](../../ixpathevaluator)
* 部件 [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->