﻿---
title: time_stamp property
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 240
url: /python-net/aspose.svg.dom.events/documentloaderrorevent/time_stamp/
is_root: false
---

## time_stamp property


Used to specify the time (in milliseconds relative to the epoch) at which the event was created.
Due to the fact that some systems may not provide this information the value of timeStamp may be not available for all events.
When not available, a value of 0 will be returned.
Examples of epoch time are the time of the system start or 0:0:0 UTC 1st January 1970.
### Definition:
```python
@property
def time_stamp(self):
    ...
```

### See Also
* module [`aspose.svg.dom.events`](../../)
* class [`DocumentLoadErrorEvent`](/svg/python-net/aspose.svg.dom.events/documentloaderrorevent)