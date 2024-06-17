﻿---
title: evaluate method
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/aspose.svg.dom.xpath/ixpathexpression/evaluate/
is_root: false
---

## evaluate {#aspose.svg.dom.Node-aspose.svg.dom.xpath.XPathResultType-any}

Evaluates this XPath expression and returns a result.


### Returns 


The result of the evaluation of the XPath expression. For XPath 1.0 results, this object will be 
of type [`IXPathResult`](/svg/python-net/aspose.svg.dom.xpath/ixpathresult).


```python
def evaluate(self, context_node, type, result):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| context_node | [`Node`](/svg/python-net/aspose.svg.dom/node) | The `context` is context node for the evaluation of this XPath expression. 
| type | [`XPathResultType`](/svg/python-net/aspose.svg.dom.xpath/xpathresulttype) | If a specific `type` is specified, then the result will be coerced to return the 
| result | any | The `result` specifies a specific result object which may be reused and returned 
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/svg/python-net/aspose.svg.dom/domexception) | TYPE_ERR: Raised if the result cannot be converted to return the specified type. |
| [`DOMException`](/svg/python-net/aspose.svg.dom/domexception) | WRONG_DOCUMENT_ERR: The Node is from a document that is not supported by 
| [`DOMException`](/svg/python-net/aspose.svg.dom/domexception) | NOT_SUPPORTED_ERR: The Node is not a type permitted as an XPath context node 





### See Also
* module [`aspose.svg.dom.xpath`](../../)
* class [`Attr`](/svg/python-net/aspose.svg.dom/attr)
* class [`CDATASection`](/svg/python-net/aspose.svg.dom/cdatasection)
* class [`Comment`](/svg/python-net/aspose.svg.dom/comment)
* class [`DOMException`](/svg/python-net/aspose.svg.dom/domexception)
* class [`Document`](/svg/python-net/aspose.svg.dom/document)
* class [`Element`](/svg/python-net/aspose.svg.dom/element)
* class [`IXPathEvaluator`](/svg/python-net/aspose.svg.dom.xpath/ixpathevaluator)
* class [`IXPathExpression`](/svg/python-net/aspose.svg.dom.xpath/ixpathexpression)
* class [`IXPathResult`](/svg/python-net/aspose.svg.dom.xpath/ixpathresult)
* class [`ProcessingInstruction`](/svg/python-net/aspose.svg.dom/processinginstruction)
* class [`Text`](/svg/python-net/aspose.svg.dom/text)
* class [`XPathResultType`](/svg/python-net/aspose.svg.dom.xpath/xpathresulttype)