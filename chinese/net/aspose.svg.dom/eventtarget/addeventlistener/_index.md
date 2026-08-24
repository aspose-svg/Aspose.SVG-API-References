---
title: "EventTarget.AddEventListener"
second_title: "Aspose.SVG for .NET API 参考"
description: "EventTarget AddEventListener 方法。设置一个函数，当指定的事件被发送到目标时将被调用。"
type: docs
weight: 20
url: /zh/net/aspose.svg.dom/eventtarget/addeventlistener/
---
## AddEventListener(*string, [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/), bool*) {#addeventlistener}

设置一个函数，当指定事件被传递到目标时将被调用。

它的工作原理是向调用所在的 [`EventTarget`](../) 上指定事件类型的事件监听器列表中添加一个函数，或实现了 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 的对象。如果该函数或对象已经在此目标的事件监听器列表中，则不会再次添加。

```csharp
public void AddEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 用户正在注册的事件类型 |
| handler | DOMEventHandler | 接受一个将在事件发生时被调用的 [`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/)。 |
| useCapture | Boolean | 如果为 true，useCapture 表示用户希望启动捕获。启动捕获后，所有指定类型的事件将在分派给树中其下的任何 Event Target 之前，先分派给已注册的 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/)。在树中向上冒泡的事件不会触发被指定为使用捕获的 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/)。 |

## 备注

如果在 [`EventTarget`](../) 正在处理事件时向其添加了 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/)，则它不会在当前操作中被触发，但可能在事件流的后续阶段（例如冒泡阶段）被触发。

如果在同一 [`EventTarget`](../) 上使用相同参数注册了多个相同的事件监听器，重复的实例将被丢弃。它们不会导致 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 被调用两次，并且由于已被丢弃，无需使用 [`RemoveEventListener`](../removeeventlistener/) 方法将其移除。

### 另请参阅

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)*) {#addeventlistener_1}

设置一个函数，当指定事件被传递到目标时将被调用。

它的工作原理是向调用所在的 [`EventTarget`](../) 上指定事件类型的事件监听器列表中添加一个函数，或实现了 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 的对象。如果该函数或对象已经在此目标的事件监听器列表中，则不会再次添加。

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 用户正在注册的事件类型 |
| 监听器 | IEventListener | 接受用户实现的接口，其中包含事件发生时要调用的方法。 |

## 备注

如果在 [`EventTarget`](../) 正在处理事件时向其添加了 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/)，则它不会在当前操作中被触发，但可能在事件流的后续阶段（例如冒泡阶段）被触发。

如果在同一 [`EventTarget`](../) 上使用相同参数注册了多个相同的事件监听器，重复的实例将被丢弃。它们不会导致 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 被调用两次，并且由于已被丢弃，无需使用 [`RemoveEventListener`](../removeeventlistener/) 方法将其移除。

### 另请参阅

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/), bool*) {#addeventlistener_2}

设置一个函数，当指定事件被传递到目标时将被调用。

它的工作原理是向调用所在的 [`EventTarget`](../) 上指定事件类型的事件监听器列表中添加一个函数，或实现了 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 的对象。如果该函数或对象已经在此目标的事件监听器列表中，则不会再次添加。

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 用户正在注册的事件类型 |
| 监听器 | IEventListener | 接受用户实现的接口，其中包含事件发生时要调用的方法。 |
| useCapture | Boolean | 如果为 true，useCapture 表示用户希望启动捕获。启动捕获后，所有指定类型的事件将在分派给树中其下的任何 Event Target 之前，先分派给已注册的 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/)。在树中向上冒泡的事件不会触发被指定为使用捕获的 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/)。 |

## 备注

如果在 [`EventTarget`](../) 正在处理事件时向其添加了 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/)，则它不会在当前操作中被触发，但可能在事件流的后续阶段（例如冒泡阶段）被触发。

如果在同一 [`EventTarget`](../) 上使用相同参数注册了多个相同的事件监听器，重复的实例将被丢弃。它们不会导致 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 被调用两次，并且由于已被丢弃，无需使用 [`RemoveEventListener`](../removeeventlistener/) 方法将其移除。

### 另请参阅

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
