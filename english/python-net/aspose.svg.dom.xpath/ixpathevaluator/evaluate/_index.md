﻿---
title: evaluate method
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 40
url: /python-net/aspose.svg.dom.xpath/ixpathevaluator/evaluate/
is_root: false
---

## evaluate {#str-aspose.svg.dom.Node-aspose.svg.dom.xpath.IXPathNSResolver-aspose.svg.dom.xpath.XPathResultType-any}

Evaluates an XPath expression string and returns a result of the specified type if possible.


### Returns 


The result of the evaluation of the XPath expression. For XPath 1.0 results, this object 
will be of type [`IXPathResult`](/svg/python-net/aspose.svg.dom.xpath/ixpathresult).


```python
def evaluate(self, expression, context_node, resolver, type, result):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| expression | str | The XPath expression string to be parsed and evaluated. |
| context_node | [`Node`](/svg/python-net/aspose.svg.dom/node) | The `context` is context node for the evaluation of this 
| resolver | [`IXPathNSResolver`](/svg/python-net/aspose.svg.dom.xpath/ixpathnsresolver) | The `resolver` permits translation of all prefixes, including 
| type | [`XPathResultType`](/svg/python-net/aspose.svg.dom.xpath/xpathresulttype) | If a specific `type` is specified, then the result will be returned as 
| result | any | The `result` specifies a specific result object which may be reused 
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/svg/python-net/aspose.svg.dom/domexception) | INVALID_EXPRESSION_ERR: Raised if the expression is not legal according 
| [`DOMException`](/svg/python-net/aspose.svg.dom/domexception) | TYPE_ERR: Raised if the result cannot be converted to return the 
| [`DOMException`](/svg/python-net/aspose.svg.dom/domexception) | NAMESPACE_ERR: Raised if the expression contains namespace prefixes 
| [`DOMException`](/svg/python-net/aspose.svg.dom/domexception) | WRONG_DOCUMENT_ERR: The Node is from a document that is not supported 
| [`DOMException`](/svg/python-net/aspose.svg.dom/domexception) | NOT_SUPPORTED_ERR: The Node is not a type permitted as an XPath context 





### See Also
* module [`aspose.svg.dom.xpath`](../../)
* class [`Attr`](/svg/python-net/aspose.svg.dom/attr)
* class [`CDATASection`](/svg/python-net/aspose.svg.dom/cdatasection)
* class [`Comment`](/svg/python-net/aspose.svg.dom/comment)
* class [`DOMException`](/svg/python-net/aspose.svg.dom/domexception)
* class [`Document`](/svg/python-net/aspose.svg.dom/document)
* class [`Element`](/svg/python-net/aspose.svg.dom/element)
* class [`IXPathEvaluator`](/svg/python-net/aspose.svg.dom.xpath/ixpathevaluator)
* class [`IXPathNSResolver`](/svg/python-net/aspose.svg.dom.xpath/ixpathnsresolver)
* class [`IXPathResult`](/svg/python-net/aspose.svg.dom.xpath/ixpathresult)
* class [`ProcessingInstruction`](/svg/python-net/aspose.svg.dom/processinginstruction)
* class [`Text`](/svg/python-net/aspose.svg.dom/text)
* class [`XPathResultType`](/svg/python-net/aspose.svg.dom.xpath/xpathresulttype)