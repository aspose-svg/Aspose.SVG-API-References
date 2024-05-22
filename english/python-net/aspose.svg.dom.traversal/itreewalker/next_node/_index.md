﻿---
title: next_node method
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 40
url: /python-net/aspose.svg.dom.traversal/itreewalker/next_node/
is_root: false
---

## next_node {#}

Moves the TreeWalker to the next visible node in document
order relative to the current node, and returns the new node. If the
current node has no next node, or if the search for nextNode attempts
to step upward from the TreeWalker's root
node, returns null, and retains the current node.


### Returns 


The new node, or null if the current node has no
next node  in the TreeWalker's logical view.


```python
def next_node(self):
    ...
```





### See Also
* module [`aspose.svg.dom.traversal`](../../)
* class [`ITreeWalker`](/svg/python-net/aspose.svg.dom.traversal/itreewalker)
