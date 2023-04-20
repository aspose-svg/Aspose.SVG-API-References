---
title: Document.CreateExpression
second_title: Aspose.SVG for .NET API 参考
description: Document 方法. 使用已解析的命名空间创建已解析的 XPath 表达式当表达式将在应用程序中重用时这很有用 因为它可以 将表达式字符串编译为更有效的内部形式并 预解析表达式中出现的所有名称空间前缀
type: docs
weight: 890
url: /zh/net/aspose.svg.dom/document/createexpression/
---
## Document.CreateExpression method

使用已解析的命名空间创建已解析的 XPath 表达式。当表达式将在应用程序中重用时，这很有用 ，因为它可以 将表达式字符串编译为更有效的内部形式，并 预解析表达式中出现的所有名称空间前缀。

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| expression | String | 要解析的 XPath 表达式字符串。 |
| resolver | IXPathNSResolver | 这`解析器`允许翻译所有前缀， 包括`XML`命名空间前缀，在 XPath 表达式中转换为 适当的命名空间 URI。如果指定为`无效的` 表达式中的任何命名空间 前缀都将导致[`DOMException`](../../domexception/)被 与代码一起抛出`命名空间_错误`. |

### 返回值

XPath 表达式的编译形式。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../domexception/) | INVALID_EXPRESSION_ERR：如果表达式 根据规则不合法则引发[`IXPathEvaluator`](../../../aspose.svg.dom.xpath/ixpathevaluator/). |
| [DOMException](../../domexception/) | NAMESPACE_ERR：如果表达式包含无法由指定的命名空间 前缀解析，则引发[`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/). |

### 也可以看看

* interface [IXPathExpression](../../../aspose.svg.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* 命名空间 [Aspose.Svg.Dom](../../document/)
* 部件 [Aspose.SVG](../../../)


