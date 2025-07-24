﻿---
title: get_element_by_id method
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 230
url: /python-net/aspose.svg.dom/document/get_element_by_id/
is_root: false
---

## get_element_by_id {#str}

This method returns an [`Element`](/svg/python-net/aspose.svg.dom/element) object representing the element whose id property matches the specified string. Since element IDs are required to be unique if specified, they're a useful way to get access to a specific element quickly.


If you need to get access to an element which doesn't have an ID, you can use [`Document.query_selector`](/svg/python-net/aspose.svg.dom/document/query_selector) to find the element using any selector.


### Returns 


An [`Element`](/svg/python-net/aspose.svg.dom/element) object describing the DOM element object matching the specified ID, or null if no matching element was found in the document.


```python
def get_element_by_id(self, element_id):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| element_id | str | The ID of the element to locate. The ID is case-sensitive string which is unique within the document; only one element may have any given ID. |
### Remarks

Refer to official [spec](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid).


### See Also
* module [`aspose.svg.dom`](../../)
* class [`Document`](/svg/python-net/aspose.svg.dom/document)
* class [`Element`](/svg/python-net/aspose.svg.dom/element)
