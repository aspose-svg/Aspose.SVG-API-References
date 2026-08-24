---
title: "EventTarget.RemoveEventListener"
second_title: "Aspose.SVG for .NET API 参考"
description: "EventTarget RemoveEventListener 方法。此方法允许从事件目标中移除事件监听器。如果在 EventTarget 正在处理事件时移除了 IEventListener，则它不会在当前操作中被触发。事件监听器在被移除后永远不会被调用。"
type: docs
weight: 50
url: /zh/net/aspose.svg.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(*string, [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/), bool*) {#removeeventlistener}

此方法允许从事件目标中移除事件监听器。如果在 [`EventTarget`](../) 正在处理事件时移除了 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/)，则它不会在当前操作中被触发。事件监听器在被移除后永远不会被调用。

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 指定被移除的 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 的事件类型。 |
| handler | DOMEventHandler | ``[`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/)`` 参数指示要移除的 ``[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/)``。 |
| useCapture | Boolean | 指定被移除的 EventListener 是否已注册为捕获监听器。如果同一监听器注册了两次，一次为捕获模式，一次为非捕获模式，则必须分别移除。移除捕获监听器不会影响同一监听器的非捕获版本，反之亦然。 |

### 另请参阅

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)*) {#removeeventlistener_1}

此方法允许从事件目标中移除事件监听器。如果在 [`EventTarget`](../) 正在处理事件时移除了 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/)，则它不会在当前操作中被触发。事件监听器在被移除后永远不会被调用。

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 指定被移除的 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 的事件类型。 |
| listener | IEventListener | 参数 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 表示要移除的 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/)。 |

### 另请参阅

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/), bool*) {#removeeventlistener_2}

此方法允许从事件目标中移除事件监听器。如果在 [`EventTarget`](../) 正在处理事件时移除了 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/)，则它不会在当前操作中被触发。事件监听器在被移除后永远不会被调用。

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 指定被移除的 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 的事件类型。 |
| listener | IEventListener | 参数 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 表示要移除的 [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/)。 |
| useCapture | Boolean | 指定被移除的 EventListener 是否已注册为捕获监听器。如果同一监听器注册了两次，一次为捕获模式，一次为非捕获模式，则必须分别移除。移除捕获监听器不会影响同一监听器的非捕获版本，反之亦然。 |

### 另请参阅

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
