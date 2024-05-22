﻿---
title: toggle method
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 80
url: /python-net/aspose.svg.collections/domtokenlist/toggle/
is_root: false
---

## toggle {#str}

Removes the token from the list if it exists, or adds the token to the list if it doesn't.


### Returns 


A Boolean indicating whether token is in the list after the call.


```python
def toggle(self, token):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| token | str | The token you want to toggle. |


## toggle {#str-bool}

Removes the token from the list if it exists, or adds the token to the list if it doesn't.


### Returns 


A Boolean indicating whether token is in the list after the call.


```python
def toggle(self, token, force):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| token | str | The token you want to toggle. |
| force | bool | A Boolean that, if included, turns the toggle into a one way-only operation. If set to false, then token will only be removed, but not added. If set to true, then token will only be added, but not removed. |



### See Also
* module [`aspose.svg.collections`](../../)
* class [`DOMTokenList`](/svg/python-net/aspose.svg.collections/domtokenlist)
