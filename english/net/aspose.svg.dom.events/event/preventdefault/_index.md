---
title: Event.PreventDefault
second_title: Aspose.SVG for .NET API Reference
description: Event PreventDefault method. If an event is cancelable the PreventDefault method is used to signify that the event is to be canceled meaning any default action normally taken by the implementation as a result of the event will not occur
type: docs
weight: 120
url: /net/aspose.svg.dom.events/event/preventdefault/
---
## Event.PreventDefault method

If an event is cancelable, the `PreventDefault` method is used to signify that the event is to be canceled, meaning any default action normally taken by the implementation as a result of the event will not occur.

```csharp
public void PreventDefault()
```

## Remarks

If, during any stage of event flow, the `PreventDefault` method is called the event is canceled. Any default action associated with the event will not occur. Calling this method for a non-cancelable event has no effect. Once `PreventDefault` has been called it will remain in effect throughout the remainder of the event's propagation. This method may be used during any stage of event flow.

### See Also

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
