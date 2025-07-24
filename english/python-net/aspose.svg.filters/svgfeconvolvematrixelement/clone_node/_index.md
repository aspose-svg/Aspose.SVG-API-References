﻿---
title: clone_node method
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 50
url: /python-net/aspose.svg.filters/svgfeconvolvematrixelement/clone_node/
is_root: false
---

## clone_node {#}

Returns a duplicate of the node on which this method was called.


Cloning a node copies all of its attributes and their values, including intrinsic (inline) listeners. It does not copy event listeners added using [`IEventTarget.add_event_listener`](/svg/python-net/aspose.svg.dom.events/ieventtarget/add_event_listener) or those assigned to element properties (e.g., node.onclick = someFunction). Additionally, for a HTMLCanvasElement element, the painted image is not copied.


### Returns 


The new [`Node`](/svg/python-net/aspose.svg.dom/node) cloned. The cloned node has no parent and is not part of the document, until it is added to another node that is part of the document, using [`Node.append_child`](/svg/python-net/aspose.svg.dom/node/append_child) or a similar method.


```python
def clone_node(self):
    ...
```




## clone_node {#bool}

Returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not.


Cloning a node copies all of its attributes and their values, including intrinsic (inline) listeners. 
It does not copy event listeners added using [`IEventTarget.add_event_listener`](/svg/python-net/aspose.svg.dom.events/ieventtarget/add_event_listener)
or those assigned to element properties (e.g., node.onclick = someFunction). Additionally, for a HTMLCanvasElement element, the painted image is not copied.


### Returns 


The new [`Node`](/svg/python-net/aspose.svg.dom/node) cloned. The cloned node has no parent and is not part of the document, 
until it is added to another node that is part of the document, using [`Node.append_child`](/svg/python-net/aspose.svg.dom/node/append_child) or a similar method.


```python
def clone_node(self, deep):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| deep | bool | If , then the node and its whole subtree, including text that may be in child [`Text`](/svg/python-net/aspose.svg.dom/text) nodes, is also copied.<br/><br/><br/>If , only the node will be cloned. The subtree, including any text that the node contains, is not cloned.<br/><br/><br/>Note that deep has no effect on empty elements, such as the  and  elements. |



### See Also
* module [`aspose.svg.filters`](../../)
* class [`Node`](/svg/python-net/aspose.svg.dom/node)
* class [`SVGFEConvolveMatrixElement`](/svg/python-net/aspose.svg.filters/svgfeconvolvematrixelement)
* class [`Text`](/svg/python-net/aspose.svg.dom/text)
