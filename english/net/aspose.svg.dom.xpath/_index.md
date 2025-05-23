---
title: Aspose.Svg.Dom.XPath
second_title: Aspose.SVG for .NET API Reference
description: The Aspose.Svg.Dom.XPath namespace contains methods to navigate through elements and attributes in an XML document
type: docs
weight: 150
url: /net/aspose.svg.dom.xpath/
---
The **Aspose.Svg.Dom.XPath** namespace contains methods to navigate through elements and attributes in an XML document.

## Interfaces

| Interface | Description |
| --- | --- |
| [IXPathEvaluator](./ixpathevaluator/) | The evaluation of XPath expressions is provided by [`IXPathEvaluator`](../aspose.svg.dom.xpath/ixpathevaluator/). |
| [IXPathExpression](./ixpathexpression/) | The `XPathExpression` interface represents a parsed and resolved XPath expression. |
| [IXPathNamespace](./ixpathnamespace/) | The XPathNamespace interface is returned by XPathResult interfaces to represent the XPath namespace node type that DOM lacks. |
| [IXPathNSResolver](./ixpathnsresolver/) | The `XPathNSResolver` interface permit `prefix` strings in the expression to be properly bound to `namespaceURI` strings. [`IXPathEvaluator`](../aspose.svg.dom.xpath/ixpathevaluator/) can construct an implementation of [`IXPathNSResolver`](../aspose.svg.dom.xpath/ixpathnsresolver/) from a node, or the interface may be implemented by any application. |
| [IXPathResult](./ixpathresult/) | The `XPathResult` interface represents the result of the evaluation of an XPath 1.0 expression within the context of a particular node. Since evaluation of an XPath expression can result in various result types, this object makes it possible to discover and manipulate the type and value of the result. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [XPathResultType](./xpathresulttype/) | An unsigned short indicating what type of result this is. If a specific `type` is specified, then the result will be returned as the corresponding type, using XPath type conversions where required and possible. |
