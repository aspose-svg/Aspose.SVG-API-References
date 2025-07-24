﻿---
title: get_elements_by_class_name method
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 240
url: /python-net/aspose.svg.dom/document/get_elements_by_class_name/
is_root: false
---

## get_elements_by_class_name {#str}

This method returns an array-like object of all child elements which have all the given class name(s).


When called on the document object, the complete document is searched, including the root node. 
You may also call this method on any element; it will return only elements which are descendants 
of the specified root element with the given class name(s).


### Returns 


A live [`HTMLCollection`](/svg/python-net/aspose.svg.collections/htmlcollection) of found elements.


```python
def get_elements_by_class_name(self, class_names):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| class_names | str | The string that contains an unordered set of unique space-separated tokens representing classes (class names) |
### Remarks

Refer to official [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname).


### See Also
* module [`aspose.svg.dom`](../../)
* class [`Document`](/svg/python-net/aspose.svg.dom/document)
* class [`HTMLCollection`](/svg/python-net/aspose.svg.collections/htmlcollection)
