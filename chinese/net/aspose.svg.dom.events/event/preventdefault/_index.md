---
title: "Event.PreventDefault"
second_title: "Aspose.SVG for .NET API 参考"
description: "Event PreventDefault 方法。如果事件是可取消的，PreventDefault 方法用于表示该事件应被取消，即实现通常因该事件而执行的任何默认操作都不会发生。"
type: docs
weight: 120
url: /zh/net/aspose.svg.dom.events/event/preventdefault/
---
## Event.PreventDefault method

如果事件是可取消的，`PreventDefault` 方法用于表示该事件应被取消，即实现通常因该事件而执行的任何默认操作都不会发生。

```csharp
public void PreventDefault()
```

## 备注

如果在事件流的任何阶段调用 `PreventDefault` 方法，事件将被取消。与该事件关联的任何默认操作都不会执行。对不可取消的事件调用此方法不会产生任何影响。一旦调用了 `PreventDefault`，它将在事件传播的剩余阶段保持有效。此方法可在事件流的任何阶段使用。

### 另请参阅

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
