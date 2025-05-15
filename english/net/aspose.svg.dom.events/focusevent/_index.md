---
title: FocusEvent Class
second_title: Aspose.SVG for .NET API Reference
description: Aspose.Svg.Dom.Events.FocusEvent class. The FocusEvent interface provides specific contextual information associated with Focus events
type: docs
weight: 2930
url: /net/aspose.svg.dom.events/focusevent/
---
## FocusEvent class

The FocusEvent interface provides specific contextual information associated with Focus events.

```csharp
public class FocusEvent : UIEvent
```

## Constructors

| Name | Description |
| --- | --- |
| [FocusEvent](focusevent/#constructor)(*string*) | Initializes a new instance of the `FocusEvent` class. |
| [FocusEvent](focusevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | Initializes a new instance of the `FocusEvent` class. |

## Properties

| Name | Description |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Used to indicate whether or not an event is a bubbling event. If the event can bubble the value is true, else the value is false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Used to indicate whether or not an event can have its default action prevented. If the default action can be prevented the value is true, else the value is false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Used to indicate the [`IEventTarget`](../ieventtarget/) whose [`IEventListener`](../ieventlistener/)s are currently being processed. This is particularly useful during capturing and bubbling. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Returns true if preventDefault() was invoked while the cancelable attribute value is true, and false otherwise. |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | Specifies some detail information about the Event, depending on the type of event. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Used to indicate which phase of event flow is currently being evaluated. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | The isTrusted attribute must return the value it was initialized to. When an event is created the attribute must be initialized to false. |
| [RelatedTarget](../../aspose.svg.dom.events/focusevent/relatedtarget/) { get; } | Used to identify a secondary EventTarget related to a Focus event, depending on the type of event. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Used to indicate the [`IEventTarget`](../ieventtarget/) to which the event was originally dispatched. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Used to specify the time (in milliseconds relative to the epoch) at which the event was created. Due to the fact that some systems may not provide this information the value of timeStamp may be not available for all events. When not available, a value of 0 will be returned. Examples of epoch time are the time of the system start or 0:0:0 UTC 1st January 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | The name of the event (case-insensitive). The name must be an XML name. |
| [View](../../aspose.svg.dom.events/uievent/view/) { get; } | The view attribute identifies the Window from which the event was generated. The un-initialized value of this attribute MUST be null. |

## Methods

| Name | Description |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | This method is used to retrieve ECMAScript object Type. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | The [`InitEvent`](../event/initevent/) method is used to initialize the value of an [`Event`](../event/) created through the [`IDocumentEvent`](../idocumentevent/) interface. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | If an event is cancelable, the [`PreventDefault`](../event/preventdefault/) method is used to signify that the event is to be canceled, meaning any default action normally taken by the implementation as a result of the event will not occur. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | The [`StopPropagation`](../event/stoppropagation/) method is used prevent further propagation of an event during event flow. |

### See Also

* class [UIEvent](../uievent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
