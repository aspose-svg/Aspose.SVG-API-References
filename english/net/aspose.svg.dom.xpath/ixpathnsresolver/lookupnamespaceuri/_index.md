---
title: IXPathNSResolver.LookupNamespaceURI
second_title: Aspose.SVG for .NET API Reference
description: IXPathNSResolver method. Look up the namespace URI associated to the given namespace prefix. The XPath evaluator must never call this with a null or empty argument because the result of doing this is undefined
type: docs
weight: 10
url: /net/aspose.svg.dom.xpath/ixpathnsresolver/lookupnamespaceuri/
---
## IXPathNSResolver.LookupNamespaceURI method

Look up the namespace URI associated to the given namespace prefix. The XPath evaluator must never call this with a `null` or empty argument, because the result of doing this is undefined.

```csharp
public string LookupNamespaceURI(string prefix)
```

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | String | The prefix to look for. |

### Return Value

Returns the associated namespace URI or `null` if none is found.

### See Also

* interface [IXPathNSResolver](../)
* namespace [Aspose.Svg.Dom.XPath](../../ixpathnsresolver/)
* assembly [Aspose.SVG](../../../)
