﻿---
title: accept_node method
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/aspose.svg.dom.traversal.filters/nodefilter/accept_node/
is_root: false
---

## accept_node {#aspose.svg.dom.Node}

Test whether a specified node is visible in the logical view of a
TreeWalker or NodeIterator. This function
will be called by the implementation of TreeWalker and
NodeIterator; it is not normally called directly from
user code. (Though you could do so if you wanted to use the same
filter to guide your own application logic.)


### Returns 


a constant to determine whether the node is accepted,
rejected, or skipped, as defined above.


```python
def accept_node(self, n):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| n | [`Node`](/svg/python-net/aspose.svg.dom/node) | node to check to see if it passes the filter or not. |



### See Also
* module [`aspose.svg.dom.traversal.filters`](../../)
* class [`NodeFilter`](/svg/python-net/aspose.svg.dom.traversal.filters/nodefilter)
