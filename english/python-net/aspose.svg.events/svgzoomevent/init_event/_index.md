﻿---
title: init_event method
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 30
url: /python-net/aspose.svg.events/svgzoomevent/init_event/
is_root: false
---

## init_event {#str-bool-bool}

The [`Event.init_event`](/svg/python-net/aspose.svg.dom.events/event/init_event) method is used to initialize the value of an [`Event`](/svg/python-net/aspose.svg.dom.events/event) created through the
[`IDocumentEvent`](/svg/python-net/aspose.svg.dom.events/idocumentevent) interface.



```python
def init_event(self, type, bubbles, cancelable):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | str | The event type. |
| bubbles | bool | if set to `true` [bubbles]. |
| cancelable | bool | if set to `true` [cancelable]. |
### Remarks

This method may only be called before the Event has been dispatched via the [`IEventTarget.dispatch_event`](/svg/python-net/aspose.svg.dom.events/ieventtarget/dispatch_event) method,
though it may be called multiple times during that phase if necessary.
If called multiple times the final invocation takes precedence.
If called from a subclass of Event interface only the values specified in the initEvent method are modified, all other attributes are left unchanged.


### See Also
* module [`aspose.svg.events`](../../)
* class [`Event`](/svg/python-net/aspose.svg.dom.events/event)
* class [`IDocumentEvent`](/svg/python-net/aspose.svg.dom.events/idocumentevent)
* class [`SVGZoomEvent`](/svg/python-net/aspose.svg.events/svgzoomevent)
