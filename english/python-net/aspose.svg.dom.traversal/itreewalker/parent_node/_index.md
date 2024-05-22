﻿---
title: parent_node method
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 60
url: /python-net/aspose.svg.dom.traversal/itreewalker/parent_node/
is_root: false
---

## parent_node {#}

Moves to and returns the closest visible ancestor node of the current
node. If the search for parentNode attempts to step
upward from the TreeWalker's root node, or
if it fails to find a visible ancestor node, this method retains the
current position and returns null.


### Returns 


The new parent node, or null if the current node
has no parent  in the TreeWalker's logical view.


```python
def parent_node(self):
    ...
```





### See Also
* module [`aspose.svg.dom.traversal`](../../)
* class [`ITreeWalker`](/svg/python-net/aspose.svg.dom.traversal/itreewalker)
