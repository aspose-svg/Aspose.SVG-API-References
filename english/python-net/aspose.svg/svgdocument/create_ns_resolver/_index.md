﻿---
title: create_ns_resolver method
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 170
url: /python-net/aspose.svg/svgdocument/create_ns_resolver/
is_root: false
---

## create_ns_resolver {#aspose.svg.dom.Node}

Adapts any DOM node to resolve namespaces so that an XPath expression can be easily evaluated
relative to the context of the node where it appeared within the document. This adapter works
like the DOM Level 3 method `lookupNamespaceURI` on nodes in resolving the namespaceURI
from a given prefix using the current information available in the node's hierarchy at the time
lookupNamespaceURI is called, also correctly resolving the implicit xml prefix.


### Returns 


[`IXPathNSResolver`](/svg/python-net/aspose.svg.dom.xpath/ixpathnsresolver) which resolves namespaces with respect to the definitions in scope for a specified node.


```python
def create_ns_resolver(self, node_resolver):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| node_resolver | aspose.svg.dom.Node | The node to be used as a context for namespace resolution. |



### See Also
* module [`aspose.svg`](../../)
* class [`IXPathNSResolver`](/svg/python-net/aspose.svg.dom.xpath/ixpathnsresolver)
* class [`SVGDocument`](/svg/python-net/aspose.svg/svgdocument)
