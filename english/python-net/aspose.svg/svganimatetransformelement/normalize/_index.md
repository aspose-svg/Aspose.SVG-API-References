﻿---
title: normalize method
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 260
url: /python-net/aspose.svg/svganimatetransformelement/normalize/
is_root: false
---

## normalize {#}

Puts all Text nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., elements, comments, processing instructions, CDATA sections, and entity references) separates Text nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the DOMConfiguration object attached to the Node.ownerDocument is true, this method will also fully normalize the characters of the Text nodes.



```python
def normalize(self):
    ...
```





### See Also
* module [`aspose.svg`](../../)
* class [`SVGAnimateTransformElement`](/svg/python-net/aspose.svg/svganimatetransformelement)
