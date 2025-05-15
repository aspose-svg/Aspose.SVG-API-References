---
title: IXPathEvaluator Interface
second_title: Aspose.SVG for .NET API Reference
description: Aspose.Svg.Dom.XPath.IXPathEvaluator interface. The evaluation of XPath expressions is provided by IXPathEvaluator
type: docs
weight: 3310
url: /net/aspose.svg.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

The evaluation of XPath expressions is provided by `IXPathEvaluator`.

```csharp
public interface IXPathEvaluator
```

## Methods

| Name | Description |
| --- | --- |
| [CreateExpression](../../aspose.svg.dom.xpath/ixpathevaluator/createexpression/)(*string, [IXPathNSResolver](../ixpathnsresolver/)*) | Creates a parsed XPath expression with resolved namespaces. This is useful when an expression will be reused in an application since it makes it possible to compile the expression string into a more efficient internal form and preresolve all namespace prefixes which occur within the expression. |
| [CreateNSResolver](../../aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/)(*[Node](../../aspose.svg.dom/node/)*) | Adapts any DOM node to resolve namespaces so that an XPath expression can be easily evaluated relative to the context of the node where it appeared within the document. This adapter works like the DOM Level 3 method `lookupNamespaceURI` on nodes in resolving the namespaceURI from a given prefix using the current information available in the node's hierarchy at the time lookupNamespaceURI is called, also correctly resolving the implicit xml prefix. |
| [Evaluate](../../aspose.svg.dom.xpath/ixpathevaluator/evaluate/)(*string, [Node](../../aspose.svg.dom/node/), [IXPathNSResolver](../ixpathnsresolver/), [XPathResultType](../xpathresulttype/), object*) | Evaluates an XPath expression string and returns a result of the specified type if possible. |

### See Also

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
