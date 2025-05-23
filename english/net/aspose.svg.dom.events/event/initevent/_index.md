---
title: Event.InitEvent
second_title: Aspose.SVG for .NET API Reference
description: Event InitEvent method. The InitEvent method is used to initialize the value of an Event created through the IDocumentEvent interface
type: docs
weight: 110
url: /net/aspose.svg.dom.events/event/initevent/
---
## Event.InitEvent method

The `InitEvent` method is used to initialize the value of an [`Event`](../) created through the [`IDocumentEvent`](../../idocumentevent/) interface.

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | String | The event type. |
| bubbles | Boolean | if set to `true` [bubbles]. |
| cancelable | Boolean | if set to `true` [cancelable]. |

## Remarks

This method may only be called before the Event has been dispatched via the [`DispatchEvent`](../../ieventtarget/dispatchevent/) method, though it may be called multiple times during that phase if necessary. If called multiple times the final invocation takes precedence. If called from a subclass of Event interface only the values specified in the initEvent method are modified, all other attributes are left unchanged.

### See Also

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
