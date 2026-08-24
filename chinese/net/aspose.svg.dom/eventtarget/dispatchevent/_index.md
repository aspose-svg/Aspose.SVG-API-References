---
title: "EventTarget.DispatchEvent"
second_title: "Aspose.SVG for .NET API 参考"
description: "EventTarget DispatchEvent 方法。将在指定的 IEventTarget 上同步分派一个事件，并按适当顺序调用受影响的事件监听器。正常的事件处理规则，包括捕获阶段和可选的冒泡阶段，也适用于使用 DispatchEvent 手动分派的事件。"
type: docs
weight: 30
url: /zh/net/aspose.svg.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

在指定的 [`IEventTarget`](../../../aspose.svg.dom.events/ieventtarget/) 上分派一个事件（同步），并按适当顺序调用受影响的事件监听器。正常的事件处理规则（包括捕获阶段和可选的冒泡阶段）同样适用于使用 [`DispatchEvent`](../../../aspose.svg.dom.events/ieventtarget/dispatchevent/) 手动分派的事件。

```csharp
public bool DispatchEvent(Event @event)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| event | 事件 | 指定用于处理事件的事件类型、行为和上下文信息。 |

### 返回值

`DispatchEvent` 的返回值指示处理该事件的监听器是否调用了 [`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/)。如果调用了 [`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/)，返回值为 false；否则返回值为 true。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../domexception/) |  |

## 备注

以这种方式分派的事件将具有与实现直接分派的事件相同的捕获和冒泡行为。事件的目标是调用 `DispatchEvent` 的 [`EventTarget`](../)。

### 另请参阅

* class [Event](../../../aspose.svg.dom.events/event/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
