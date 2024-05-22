﻿---
title: get_screen_ctm method
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 180
url: /python-net/aspose.svg/svgdefselement/get_screen_ctm/
is_root: false
---

## get_screen_ctm {#}

Returns the transformation matrix from current user units (i.e., after application of the ‘transform’ attribute, if any) to the parent user agent's notice of a "pixel". For display devices, ideally this represents a physical screen pixel. For other devices or environments where physical pixel sizes are not known, then an algorithm similar to the CSS2 definition of a "pixel" can be used instead. Note that null is returned if this element is not hooked into the document tree. This method would have been more aptly named as getClientCTM, but the name getScreenCTM is kept for historical reasons.


### Returns 


An SVGMatrix object that defines the given transformation matrix.


```python
def get_screen_ctm(self):
    ...
```





### See Also
* module [`aspose.svg`](../../)
* class [`SVGDefsElement`](/svg/python-net/aspose.svg/svgdefselement)
* class [`SVGMatrix`](/svg/python-net/aspose.svg.datatypes/svgmatrix)
