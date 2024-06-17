﻿---
title: create_node_iterator method
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 160
url: /python-net/aspose.svg.dom/document/create_node_iterator/
is_root: false
---

## create_node_iterator {#aspose.svg.dom.Node}

Create a new NodeIterator over the subtree rooted at the
specified node.


### Returns 


The newly created NodeIterator.


```python
def create_node_iterator(self, root):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| root | [`Node`](/svg/python-net/aspose.svg.dom/node) | node which will be iterated together with its children.
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/svg/python-net/aspose.svg.dom/domexception) | NOT_SUPPORTED_ERR: Raised if the specified root is




## create_node_iterator {#aspose.svg.dom.Node-int}

Create a new NodeIterator over the subtree rooted at the
specified node.


### Returns 


The newly created NodeIterator.


```python
def create_node_iterator(self, root, what_to_show):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| root | [`Node`](/svg/python-net/aspose.svg.dom/node) | node which will be iterated together with its children.
| what_to_show | int | flag specifies which node types may appear in
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/svg/python-net/aspose.svg.dom/domexception) | NOT_SUPPORTED_ERR: Raised if the specified root is




## create_node_iterator {#aspose.svg.dom.Node-int-aspose.svg.dom.traversal.INodeFilter}

Create a new NodeIterator over the subtree rooted at the
specified node.


### Returns 


The newly created NodeIterator.


```python
def create_node_iterator(self, root, what_to_show, filter):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| root | [`Node`](/svg/python-net/aspose.svg.dom/node) | node which will be iterated together with its children.
| what_to_show | int | flag specifies which node types may appear in
| filter | aspose.svg.dom.traversal.INodeFilter | NodeFilter to be used with this
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/svg/python-net/aspose.svg.dom/domexception) | NOT_SUPPORTED_ERR: Raised if the specified root is





### See Also
* module [`aspose.svg.dom`](../../)
* class [`DOMException`](/svg/python-net/aspose.svg.dom/domexception)
* class [`Document`](/svg/python-net/aspose.svg.dom/document)
* class [`INodeIterator`](/svg/python-net/aspose.svg.dom.traversal/inodeiterator)