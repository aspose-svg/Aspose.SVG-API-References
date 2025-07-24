﻿---
title: UIEvent class
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 120
url: /python-net/aspose.svg.dom.events/uievent/
is_root: false
---

## UIEvent class

The UIEvent interface provides specific contextual information associated with User Interface events.



**Inheritance:** [`UIEvent`](/svg/python-net/aspose.svg.dom.events/uievent) → 
[`Event`](/svg/python-net/aspose.svg.dom.events/event) → 
[`DOMObject`](/svg/python-net/aspose.svg.dom/domobject)



The UIEvent type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/svg/python-net/aspose.svg.dom.events/uievent/__init__/#str) | Initializes a new instance of the [`UIEvent`](/svg/python-net/aspose.svg.dom.events/uievent) class. |


### Properties
| Property | Description |
| :- | :- |
| [bubbles](/svg/python-net/aspose.svg.dom.events/uievent/bubbles) | Used to indicate whether or not an event is a bubbling event. If the event can bubble the value is true, else the value is false. |
| [cancelable](/svg/python-net/aspose.svg.dom.events/uievent/cancelable) | Used to indicate whether or not an event can have its default action prevented. If the default action can be prevented the value is true, else the value is false. |
| [current_target](/svg/python-net/aspose.svg.dom.events/uievent/current_target) | Used to indicate the [`IEventTarget`](/svg/python-net/aspose.svg.dom.events/ieventtarget) whose [`IEventListener`](/svg/python-net/aspose.svg.dom.events/ieventlistener)s are currently being processed.<br/>This is particularly useful during capturing and bubbling. |
| [event_phase](/svg/python-net/aspose.svg.dom.events/uievent/event_phase) | Used to indicate which phase of event flow is currently being evaluated. |
| [target](/svg/python-net/aspose.svg.dom.events/uievent/target) | Used to indicate the [`IEventTarget`](/svg/python-net/aspose.svg.dom.events/ieventtarget) to which the event was originally dispatched. |
| [time_stamp](/svg/python-net/aspose.svg.dom.events/uievent/time_stamp) | Used to specify the time (in milliseconds relative to the epoch) at which the event was created.<br/>Due to the fact that some systems may not provide this information the value of timeStamp may be not available for all events.<br/>When not available, a value of 0 will be returned.<br/>Examples of epoch time are the time of the system start or 0:0:0 UTC 1st January 1970. |
| [type](/svg/python-net/aspose.svg.dom.events/uievent/type) | The name of the event (case-insensitive). The name must be an XML name. |
| [default_prevented](/svg/python-net/aspose.svg.dom.events/uievent/default_prevented) | Returns true if preventDefault() was invoked while the cancelable attribute value is true, and false otherwise. |
| [is_trusted](/svg/python-net/aspose.svg.dom.events/uievent/is_trusted) | The isTrusted attribute must return the value it was initialized to. When an event is created the attribute must be initialized to false. |
| [NONE_PHASE](/svg/python-net/aspose.svg.dom.events/uievent/none_phase) | Events not currently dispatched are in this phase. |
| [CAPTURING_PHASE](/svg/python-net/aspose.svg.dom.events/uievent/capturing_phase) | The event is currently being evaluated at the target [`IEventTarget`](/svg/python-net/aspose.svg.dom.events/ieventtarget). |
| [AT_TARGET_PHASE](/svg/python-net/aspose.svg.dom.events/uievent/at_target_phase) | The current event phase is the capturing phase. |
| [BUBBLING_PHASE](/svg/python-net/aspose.svg.dom.events/uievent/bubbling_phase) | The current event phase is the bubbling phase. |
| [view](/svg/python-net/aspose.svg.dom.events/uievent/view) | The view attribute identifies the Window from which the event was generated.<br/>The un-initialized value of this attribute MUST be null. |
| [detail](/svg/python-net/aspose.svg.dom.events/uievent/detail) | Specifies some detail information about the Event, depending on the type of event. |


### Methods
| Method | Description |
| :- | :- |
| [get_platform_type](/svg/python-net/aspose.svg.dom.events/uievent/get_platform_type/#) | This method is used to retrieve the ECMAScript object Type. |
| [init_event](/svg/python-net/aspose.svg.dom.events/uievent/init_event/#str-bool-bool) | The [`Event.init_event`](/svg/python-net/aspose.svg.dom.events/event/init_event) method is used to initialize the value of an [`Event`](/svg/python-net/aspose.svg.dom.events/event) created through the<br/>[`IDocumentEvent`](/svg/python-net/aspose.svg.dom.events/idocumentevent) interface. |
| [prevent_default](/svg/python-net/aspose.svg.dom.events/uievent/prevent_default/#) | If an event is cancelable, the [`Event.prevent_default`](/svg/python-net/aspose.svg.dom.events/event/prevent_default) method is used to signify that the event is to be canceled,<br/>meaning any default action normally taken by the implementation as a result of the event will not occur. |
| [stop_propagation](/svg/python-net/aspose.svg.dom.events/uievent/stop_propagation/#) | The [`Event.stop_propagation`](/svg/python-net/aspose.svg.dom.events/event/stop_propagation) method is used prevent further propagation of an event during event flow. |
| [stop_immediate_propagation](/svg/python-net/aspose.svg.dom.events/uievent/stop_immediate_propagation/#) | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |



### See Also
* module [`aspose.svg.dom.events`](..)
* class [`DOMObject`](/svg/python-net/aspose.svg.dom/domobject)
* class [`Event`](/svg/python-net/aspose.svg.dom.events/event)
* class [`IDocumentEvent`](/svg/python-net/aspose.svg.dom.events/idocumentevent)
* class [`IEventListener`](/svg/python-net/aspose.svg.dom.events/ieventlistener)
* class [`IEventTarget`](/svg/python-net/aspose.svg.dom.events/ieventtarget)
* class [`UIEvent`](/svg/python-net/aspose.svg.dom.events/uievent)
