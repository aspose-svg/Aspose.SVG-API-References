﻿---
title: prevent_default method
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 40
url: /python-net/aspose.svg.dom.events/errorevent/prevent_default/
is_root: false
---

## prevent_default {#}

If an event is cancelable, the [`Event.prevent_default`](/svg/python-net/aspose.svg.dom.events/event/prevent_default) method is used to signify that the event is to be canceled,
meaning any default action normally taken by the implementation as a result of the event will not occur.



```python
def prevent_default(self):
    ...
```


### Remarks

If, during any stage of event flow, the [`Event.prevent_default`](/svg/python-net/aspose.svg.dom.events/event/prevent_default) method is called the event is canceled.
Any default action associated with the event will not occur.
Calling this method for a non-cancelable event has no effect.
Once [`Event.prevent_default`](/svg/python-net/aspose.svg.dom.events/event/prevent_default) has been called it will remain in effect throughout the remainder of the event's propagation.
This method may be used during any stage of event flow.


### See Also
* module [`aspose.svg.dom.events`](../../)
* class [`ErrorEvent`](/svg/python-net/aspose.svg.dom.events/errorevent)
