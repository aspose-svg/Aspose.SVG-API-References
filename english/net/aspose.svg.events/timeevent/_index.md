---
title: TimeEvent Class
second_title: Aspose.SVG for .NET API Reference
description: Aspose.Svg.Events.TimeEvent class. The TimeEvent interface provides specific contextual information associated with Time events.The different types of events that can occur are beginEvent endEvent and repeatEvent
type: docs
weight: 3740
url: /net/aspose.svg.events/timeevent/
---
## TimeEvent class

The TimeEvent interface provides specific contextual information associated with Time events.The different types of events that can occur are: beginEvent, endEvent and repeatEvent.

```csharp
public class TimeEvent : Event
```

## Properties

| Name | Description |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Used to indicate whether or not an event is a bubbling event. If the event can bubble the value is true, else the value is false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Used to indicate whether or not an event can have its default action prevented. If the default action can be prevented the value is true, else the value is false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Used to indicate the [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) whose [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)s are currently being processed. This is particularly useful during capturing and bubbling. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Returns true if preventDefault() was invoked while the cancelable attribute value is true, and false otherwise. |
| [Detail](../../aspose.svg.events/timeevent/detail/) { get; } | Specifies some detail information about the Event, depending on the type of the event. For this event type, indicates the repeat number for the animation. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Used to indicate which phase of event flow is currently being evaluated. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | The isTrusted attribute must return the value it was initialized to. When an event is created the attribute must be initialized to false. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Used to indicate the [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) to which the event was originally dispatched. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Used to specify the time (in milliseconds relative to the epoch) at which the event was created. Due to the fact that some systems may not provide this information the value of timeStamp may be not available for all events. When not available, a value of 0 will be returned. Examples of epoch time are the time of the system start or 0:0:0 UTC 1st January 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | The name of the event (case-insensitive). The name must be an XML name. |
| [View](../../aspose.svg.events/timeevent/view/) { get; } | The view attribute identifies the AbstractView [DOM2VIEWS] from which the event was generated. |

## Methods

| Name | Description |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | This method is used to retrieve ECMAScript object Type. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | The [`InitEvent`](../../aspose.svg.dom.events/event/initevent/) method is used to initialize the value of an [`Event`](../../aspose.svg.dom.events/event/) created through the [`IDocumentEvent`](../../aspose.svg.dom.events/idocumentevent/) interface. |
| [InitTimeEvent](../../aspose.svg.events/timeevent/inittimeevent/)(*string, [IAbstractView](../../aspose.svg.dom.views/iabstractview/), long*) | The initTimeEvent method is used to initialize the value of a TimeEvent created through the DocumentEvent interface. This method may only be called before the TimeEvent has been dispatched via the dispatchEvent method, though it may be called multiple times during that phase if necessary. If called multiple times, the final invocation takes precedence. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | If an event is cancelable, the [`PreventDefault`](../../aspose.svg.dom.events/event/preventdefault/) method is used to signify that the event is to be canceled, meaning any default action normally taken by the implementation as a result of the event will not occur. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | The [`StopPropagation`](../../aspose.svg.dom.events/event/stoppropagation/) method is used prevent further propagation of an event during event flow. |

### See Also

* class [Event](../../aspose.svg.dom.events/event/)
* namespace [Aspose.Svg.Events](../../aspose.svg.events/)
* assembly [Aspose.SVG](../../)
