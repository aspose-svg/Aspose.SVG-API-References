---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.SVG for .NET API 参考"
description: "IEventTarget AddEventListener 方法。此方法允许在事件目标上注册事件监听器。"
type: docs
weight: 10
url: /zh/net/aspose.svg.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(*string, [IEventListener](../../ieventlistener/)*) {#addeventlistener}

此方法允许在事件目标上注册事件监听器。

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 用户正在注册的事件类型 |
| 监听器 | IEventListener | 接受用户实现的接口，其中包含事件发生时要调用的方法。 |

## 备注

如果在 [`EventTarget`](../../../aspose.svg.dom/eventtarget/) 正在处理事件时向其添加了 [`IEventListener`](../../ieventlistener/)，则不会在当前操作中触发，但可能在事件流的后期阶段（例如冒泡阶段）触发。

如果在同一 [`EventTarget`](../../../aspose.svg.dom/eventtarget/) 上使用相同参数注册了多个相同的事件监听器，重复的实例会被丢弃。它们不会导致 [`IEventListener`](../../ieventlistener/) 被调用两次，并且由于已被丢弃，无需使用 [`RemoveEventListener`](../removeeventlistener/) 方法将其移除。

### 另请参阅

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../ieventlistener/), bool*) {#addeventlistener_1}

此方法允许在事件目标上注册事件监听器。

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 用户正在注册的事件类型 |
| 监听器 | IEventListener | 接受用户实现的接口，其中包含事件发生时要调用的方法。 |
| useCapture | Boolean | 如果为 true，useCapture 表示用户希望启动捕获。启动捕获后，指定类型的所有事件将在分发给树中其下的任何事件目标之前，先分发给已注册的 [`IEventListener`](../../ieventlistener/)。在树中向上冒泡的事件不会触发标记为使用捕获的 [`IEventListener`](../../ieventlistener/)。 |

## 备注

如果在 [`EventTarget`](../../../aspose.svg.dom/eventtarget/) 正在处理事件时向其添加了 [`IEventListener`](../../ieventlistener/)，则不会在当前操作中触发，但可能在事件流的后期阶段（例如冒泡阶段）触发。

如果在同一 [`EventTarget`](../../../aspose.svg.dom/eventtarget/) 上使用相同参数注册了多个相同的事件监听器，重复的实例会被丢弃。它们不会导致 [`IEventListener`](../../ieventlistener/) 被调用两次，并且由于已被丢弃，无需使用 [`RemoveEventListener`](../removeeventlistener/) 方法将其移除。

### 另请参阅

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
