---
title: Document.CreateExpression
second_title: Aspose.SVG for .NET API Reference
description: Document method. Creates a parsed XPath expression with resolved namespaces. This is useful when an expression will be reused in an application since it makes it possible to compile the expression string into a more efficient internal form and preresolve all namespace prefixes which occur within the expression
type: docs
weight: 890
url: /net/aspose.svg.dom/document/createexpression/
---
## Document.CreateExpression method

Creates a parsed XPath expression with resolved namespaces. This is useful when an expression will be reused in an application since it makes it possible to compile the expression string into a more efficient internal form and preresolve all namespace prefixes which occur within the expression.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parameter | Type | Description |
| --- | --- | --- |
| expression | String | The XPath expression string to be parsed. |
| resolver | IXPathNSResolver | The `resolver` permits translation of all prefixes, including the `xml` namespace prefix, within the XPath expression into appropriate namespace URIs. If this is specified as `null`, any namespace prefix within the expression will result in [`DOMException`](../../domexception/) being thrown with the code `NAMESPACE_ERR`. |

### Return Value

The compiled form of the XPath expression.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Raised if the expression is not legal according to the rules of the [`IXPathEvaluator`](../../../aspose.svg.dom.xpath/ixpathevaluator/). |
| [DOMException](../../domexception/) | NAMESPACE_ERR: Raised if the expression contains namespace prefixes which cannot be resolved by the specified [`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/). |

### See Also

* interface [IXPathExpression](../../../aspose.svg.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
