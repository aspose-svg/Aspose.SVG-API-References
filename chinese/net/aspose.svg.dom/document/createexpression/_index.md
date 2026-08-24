---
title: "Document.CreateExpression"
second_title: "Aspose.SVG for .NET API 参考"
description: "Document CreateExpression 方法。创建一个已解析命名空间的 XPath 表达式。当表达式将在应用程序中重复使用时，这非常有用，因为它可以将表达式字符串编译为更高效的内部形式，并预先解析表达式中出现的所有命名空间前缀。"
type: docs
weight: 890
url: /zh/net/aspose.svg.dom/document/createexpression/
---
## Document.CreateExpression method

创建一个已解析命名空间的 XPath 表达式。这在表达式将在应用程序中重复使用时很有用，因为它可以将表达式字符串编译为更高效的内部形式，并预先解析表达式中出现的所有命名空间前缀。

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| expression | String | 待解析的 XPath 表达式字符串。 |
| resolver | IXPathNSResolver | `resolver` 允许在 XPath 表达式中翻译所有前缀，包括 `xml` 命名空间前缀，转换为相应的命名空间 URI。如果将其指定为 `null`，表达式中的任何命名空间前缀都会导致抛出 [`DOMException`](../../domexception/) 并带有代码 `NAMESPACE_ERR`。 |

### 返回值

XPath 表达式的编译形式。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../domexception/) | INVALID_EXPRESSION_ERR：如果表达式不符合 [`IXPathEvaluator`](../../../aspose.svg.dom.xpath/ixpathevaluator/) 的规则，则会抛出此错误。 |
| [DOMException](../../domexception/) | NAMESPACE_ERR：如果表达式包含无法由指定的 [`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/) 解析的命名空间前缀，则会抛出此错误。 |

### 另请参阅

* interface [IXPathExpression](../../../aspose.svg.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
