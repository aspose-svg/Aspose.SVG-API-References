﻿---
title: stop_propagation method
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 60
url: /python-net/aspose.svg.dom.events/focusevent/stop_propagation/
is_root: false
---

## stop_propagation {#}

The [`Event.stop_propagation`](/svg/python-net/aspose.svg.dom.events/event/stop_propagation) method is used prevent further propagation of an event during event flow.



```python
def stop_propagation(self):
    ...
```


### Remarks

If this method is called by any [`IEventListener`](/svg/python-net/aspose.svg.dom.events/ieventlistener) the event will cease propagating through the tree.
The event will complete dispatch to all listeners on the current [`IEventTarget`](/svg/python-net/aspose.svg.dom.events/ieventtarget) before event flow stops.
This method may be used during any stage of event flow.


### See Also
* module [`aspose.svg.dom.events`](../../)
* class [`FocusEvent`](/svg/python-net/aspose.svg.dom.events/focusevent)
* class [`IEventListener`](/svg/python-net/aspose.svg.dom.events/ieventlistener)
* class [`IEventTarget`](/svg/python-net/aspose.svg.dom.events/ieventtarget)
