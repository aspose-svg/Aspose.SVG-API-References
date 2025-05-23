---
title: Document.CreateNSResolver
second_title: Aspose.SVG for .NET API Reference
description: Document CreateNSResolver method. Adapts any DOM node to resolve namespaces so that an XPath expression can be easily evaluated relative to the context of the node where it appeared within the document. This adapter works like the DOM Level 3 method lookupNamespaceURI on nodes in resolving the namespaceURI from a given prefix using the current information available in the nodes hierarchy at the time lookupNamespaceURI is called also correctly resolving the implicit xml prefix
type: docs
weight: 910
url: /net/aspose.svg.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Adapts any DOM node to resolve namespaces so that an XPath expression can be easily evaluated relative to the context of the node where it appeared within the document. This adapter works like the DOM Level 3 method `lookupNamespaceURI` on nodes in resolving the namespaceURI from a given prefix using the current information available in the node's hierarchy at the time lookupNamespaceURI is called, also correctly resolving the implicit xml prefix.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Type | Description |
| --- | --- | --- |
| nodeResolver | Node | The node to be used as a context for namespace resolution. |

### Return Value

[`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/) which resolves namespaces with respect to the definitions in scope for a specified node.

### See Also

* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
