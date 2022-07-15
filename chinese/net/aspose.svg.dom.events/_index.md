---
title: Aspose.Svg.Dom.Events
second_title: Aspose.SVG for .NET API 参考
description: Aspose.Svg.Dom.Events 命名空间为 任何与 DOM 更新相关的事件提供对象它包括订阅 与事件相关的特定上下文信息观察 以及自定义事件构造
type: docs
weight: 80
url: /zh/net/aspose.svg.dom.events/
---
**Aspose.Svg.Dom.Events** 命名空间为 任何与 DOM 更新相关的事件提供对象。它包括订阅 与事件相关的特定上下文信息观察 以及自定义事件构造。

## 课程

| 班级 | 描述 |
| --- | --- |
| [CustomEvent](./customevent) | 使用 CustomEvent 接口的事件可用于携带自定义数据。 |
| [DocumentLoadErrorEvent](./documentloaderrorevent) | [`DocumentLoadErrorEvent`](../aspose.svg.dom.events/documentloaderrorevent)在请求的资源不可用时发生。 |
| [DOMEventHandler](./domeventhandler) | 表示事件处理的回调。 |
| [ErrorEvent](./errorevent) | [`ErrorEvent`](../aspose.svg.dom.events/errorevent)提供有关运行时发生的错误的上下文信息。 |
| [Event](./event) | [`Event`](../aspose.svg.dom.events/event)用于向处理事件的处理程序提供有关事件的上下文信息。 |
| [FocusEvent](./focusevent) | FocusEvent 接口提供与焦点事件相关的特定上下文信息。 |
| [InputEvent](./inputevent) | 每当更新 DOM 时，输入事件都会作为通知发送。 |
| [KeyboardEvent](./keyboardevent) | KeyboardEvent 接口提供与键盘设备相关的特定上下文信息。每个键盘事件都使用一个值引用一个键。键盘事件通常针对具有焦点的元素。 |
| [MouseEvent](./mouseevent) | MouseEvent 接口提供与鼠标事件相关的特定上下文信息。 |
| [UIEvent](./uievent) | UIEvent 接口提供与用户界面事件相关的特定上下文信息。 |
| [WheelEvent](./wheelevent) | WheelEvent 接口提供与车轮事件相关的特定上下文信息。要创建 WheelEvent 接口的实例，请使用 WheelEvent 构造函数，传递可选的 WheelEventInit 字典。 |
## 接口

| 界面 | 描述 |
| --- | --- |
| [IDocumentEvent](./idocumentevent) | [`IDocumentEvent`](../aspose.svg.dom.events/idocumentevent)接口提供了一种机制，用户可以通过该机制创建Event。 |
| [IEventListener](./ieventlistener) | [`IEventListener`](../aspose.svg.dom.events/ieventlistener)接口是处理事件的主要方法。 用户实现[`IEventListener`](../aspose.svg.dom.events/ieventlistener)接口并使用[`EventTarget`](../aspose.svg.dom/eventtarget)注册他们的监听器[`AddEventListener`](../aspose.svg.dom/eventtarget/addeventlistener)方法。 用户完成使用后，还应从其[`EventTarget`](../aspose.svg.dom/eventtarget)中删除其[`IEventListener`](../aspose.svg.dom.events/ieventlistener)听众。 |
| [IEventTarget](./ieventtarget) | [`EventTarget`](../aspose.svg.dom/eventtarget)接口由支持 DOM 事件模型的实现中的所有节点实现。 因此，可以通过在Node 接口的实例上使用特定于绑定的强制转换方法来获得此接口。 该接口允许在[`EventTarget`](../aspose.svg.dom/eventtarget)上注册和删除事件侦听器，并将事件分派到[`IEventTarget`](../aspose.svg.dom.events/ieventtarget)。 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->