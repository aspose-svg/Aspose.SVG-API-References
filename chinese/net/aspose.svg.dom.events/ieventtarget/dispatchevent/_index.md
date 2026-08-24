---
title: "IEventTarget.DispatchEvent"
second_title: "Aspose.SVG for .NET API 参考"
description: "IEventTarget DispatchEvent 方法。此方法允许将事件分派到实现的事件模型中"
type: docs
weight: 20
url: /zh/net/aspose.svg.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

此方法允许将事件分派到实现的事件模型中。

```csharp
public bool DispatchEvent(Event @event)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| event | 事件 | 指定用于处理事件的事件类型、行为和上下文信息。 |

### 返回值

`[`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/)` 的返回值指示是否有任何处理该事件的监听器调用了 [`PreventDefault`](../../event/preventdefault/)。如果调用了 [`PreventDefault`](../../event/preventdefault/)，则返回值为 false，否则返回值为 true。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) |  |

## 备注

以这种方式分发的事件将具有与实现直接分发的事件相同的捕获和冒泡行为。事件的目标是调用了 [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) 的 [`EventTarget`](../../../aspose.svg.dom/eventtarget/)。

### 另请参阅

* class [Event](../../event/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
