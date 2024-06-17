﻿---
title: create_tree_walker method
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 200
url: /python-net/aspose.svg.dom/document/create_tree_walker/
is_root: false
---

## create_tree_walker {#aspose.svg.dom.Node}

Create a new TreeWalker over the subtree rooted at the
specified node.


### Returns 


The newly created TreeWalker.


```python
def create_tree_walker(self, root):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| root | [`Node`](/svg/python-net/aspose.svg.dom/node) | node which will serve as the root for the
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/svg/python-net/aspose.svg.dom/domexception) | NOT_SUPPORTED_ERR: Raised if the specified root is




## create_tree_walker {#aspose.svg.dom.Node-int}

Create a new TreeWalker over the subtree rooted at the
specified node.


### Returns 


The newly created TreeWalker.


```python
def create_tree_walker(self, root, what_to_show):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| root | [`Node`](/svg/python-net/aspose.svg.dom/node) | node which will serve as the root for the
| what_to_show | int | flag specifies which node types may appear in
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/svg/python-net/aspose.svg.dom/domexception) | NOT_SUPPORTED_ERR: Raised if the specified root is




## create_tree_walker {#aspose.svg.dom.Node-int-aspose.svg.dom.traversal.INodeFilter}

Create a new TreeWalker over the subtree rooted at the
specified node.


### Returns 


The newly created TreeWalker.


```python
def create_tree_walker(self, root, what_to_show, filter):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| root | [`Node`](/svg/python-net/aspose.svg.dom/node) | node which will serve as the root for the
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
* class [`ITreeWalker`](/svg/python-net/aspose.svg.dom.traversal/itreewalker)