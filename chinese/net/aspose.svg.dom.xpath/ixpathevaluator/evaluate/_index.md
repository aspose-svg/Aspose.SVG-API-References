---
title: "IXPathEvaluator.Evaluate"
second_title: "Aspose.SVG for .NET API 参考"
description: "IXPathEvaluator Evaluate 方法。评估 XPath 表达式字符串，并在可能的情况下返回指定类型的结果。"
type: docs
weight: 30
url: /zh/net/aspose.svg.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

求值 XPath 表达式字符串，并在可能的情况下返回指定类型的结果。

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| expression | String | 待解析和评估的 XPath 表达式字符串。 |
| contextNode | Node | `context` 是用于评估此 XPath 表达式的上下文节点。如果通过将 [`Document`](../../../aspose.svg.dom/document/) 强制转换获得了 [`IXPathEvaluator`](../)，则该节点必须属于同一文档，并且必须是 [`Document`](../../../aspose.svg.dom/document/)、[`Element`](../../../aspose.svg.dom/element/)、[`Attr`](../../../aspose.svg.dom/attr/)、[`Text`](../../../aspose.svg.dom/text/)、[`CDATASection`](../../../aspose.svg.dom/cdatasection/)、[`Comment`](../../../aspose.svg.dom/comment/)、[`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/) 或 XPathNamespace 节点。如果上下文节点是 [`Text`](../../../aspose.svg.dom/text/) 或 [`CDATASection`](../../../aspose.svg.dom/cdatasection/)，则上下文被解释为 XPath 所看到的整个逻辑文本节点，除非该节点为空，此时它不能作为 XPath 上下文。 |
| resolver | IXPathNSResolver | 该 `resolver` 允许在 XPath 表达式中将所有前缀（包括 `xml` 命名空间前缀）翻译为相应的命名空间 URI。如果将其指定为 `null`，表达式中的任何命名空间前缀都会导致抛出 [`DOMException`](../../../aspose.svg.dom/domexception/) ，错误代码为 `NAMESPACE_ERR`。 |
| type | XPathResultType | 如果指定了特定的 `type`，则结果将以相应的类型返回。对于 XPath 1.0 的结果，这必须是 [`XPathResultType`](../../xpathresulttype/) 枚举中的某个值。 |
| result | Object | `result` 指定一个特定的结果对象，该对象可以被此方法复用并返回。如果将其指定为 `null`，或实现未复用指定的结果，则会创建并返回一个新的结果对象。对于 XPath 1.0 的结果，该对象的类型为 [`IXPathResult`](../../ixpathresult/)。 |

### 返回值

XPath 表达式求值的结果。对于 XPath 1.0 的结果，该对象的类型为 [`IXPathResult`](../../ixpathresult/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_EXPRESSION_ERR：如果表达式不符合 [`IXPathEvaluator`](../) 的规则，则会抛出此错误。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR：如果结果无法转换为指定的类型则抛出。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | NAMESPACE_ERR：如果表达式包含无法由指定的 [`IXPathNSResolver`](../../ixpathnsresolver/) 解析的命名空间前缀，则会抛出此错误。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR：该节点来自一个不被此 [`IXPathEvaluator`](../) 支持的文档。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR：该节点的类型不被允许作为 XPath 上下文节点，或请求的类型不被此 [`IXPathEvaluator`](../) 允许。 |

### 另请参阅

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
