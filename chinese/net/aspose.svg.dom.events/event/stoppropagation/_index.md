---
title: "Event.StopPropagation"
second_title: "Aspose.SVG for .NET API 参考"
description: "Event StopPropagation 方法。StopPropagation 方法用于在事件流期间阻止事件的进一步传播。"
type: docs
weight: 140
url: /zh/net/aspose.svg.dom.events/event/stoppropagation/
---
## Event.StopPropagation method

`StopPropagation` 方法用于在事件流期间阻止事件的进一步传播。

```csharp
public void StopPropagation()
```

## 备注

如果此方法被任何 [`IEventListener`](../../ieventlistener/) 调用，事件将在树中停止传播。事件将在当前的 [`IEventTarget`](../../ieventtarget/) 上完成对所有监听器的分发后才停止事件流。此方法可在事件流的任何阶段使用。

### 另请参阅

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
