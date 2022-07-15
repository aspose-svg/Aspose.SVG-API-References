---
title: DispatchEvent
second_title: Aspose.SVG for .NET API 参考
description: 此方法允许将事件分派到实现事件模型中
type: docs
weight: 20
url: /zh/net/aspose.svg.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

此方法允许将事件分派到实现事件模型中。

```csharp
public bool DispatchEvent(Event @event)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| event | Event | 指定用于处理事件的事件类型、行为和上下文信息。 |

### 返回值

`DispatchEvent`的返回值表示是否有任何处理称为[`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault)的事件的侦听器。 如果调用了[`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault)，则值为假，否则值为真。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../domexception) |  |

### 评论

以这种方式调度的事件将具有与由实现直接分派的事件相同的捕获和冒泡行为。 事件的目标是[`EventTarget`](../../eventtarget)上的`DispatchEvent`被调用。

### 也可以看看

* class [Event](../../../aspose.svg.dom.events/event)
* class [EventTarget](../../eventtarget)
* 命名空间 [Aspose.Svg.Dom](../../eventtarget)
* 部件 [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->