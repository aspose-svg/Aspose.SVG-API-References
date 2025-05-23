---
title: TimeEvent.InitTimeEvent
second_title: Aspose.SVG for .NET API Reference
description: TimeEvent InitTimeEvent method. The initTimeEvent method is used to initialize the value of a TimeEvent created through the DocumentEvent interface. This method may only be called before the TimeEvent has been dispatched via the dispatchEvent method though it may be called multiple times during that phase if necessary. If called multiple times the final invocation takes precedence
type: docs
weight: 30
url: /net/aspose.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

The initTimeEvent method is used to initialize the value of a TimeEvent created through the DocumentEvent interface. This method may only be called before the TimeEvent has been dispatched via the dispatchEvent method, though it may be called multiple times during that phase if necessary. If called multiple times, the final invocation takes precedence.

```csharp
public void InitTimeEvent(string typeArg, IAbstractView viewArg, long detailArg)
```

| Parameter | Type | Description |
| --- | --- | --- |
| typeArg | String | Specifies the event type. |
| viewArg | IAbstractView | Specifies the Event's AbstractView. |
| detailArg | Int64 | Specifies the Event's detail. |

### See Also

* interface [IAbstractView](../../../aspose.svg.dom.views/iabstractview/)
* class [TimeEvent](../)
* namespace [Aspose.Svg.Events](../../../aspose.svg.events/)
* assembly [Aspose.SVG](../../../)
