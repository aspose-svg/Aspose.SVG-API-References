---
title: "TimeEvent.InitTimeEvent"
second_title: "Aspose.SVG for .NET API 参考"
description: "TimeEvent InitTimeEvent 方法。initTimeEvent 方法用于初始化通过 DocumentEvent 接口创建的 TimeEvent 的值。此方法只能在 TimeEvent 通过 dispatchEvent 方法分发之前调用，尽管在该阶段如有必要可以多次调用。如果多次调用，则以最后一次调用为准。"
type: docs
weight: 30
url: /zh/net/aspose.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

initTimeEvent 方法用于初始化通过 DocumentEvent 接口创建的 TimeEvent 的值。此方法只能在 TimeEvent 通过 dispatchEvent 方法分发之前调用，尽管在该阶段如有必要可以多次调用。如果多次调用，则以最后一次调用为准。

```csharp
public void InitTimeEvent(string typeArg, IAbstractView viewArg, long detailArg)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| typeArg | String | 指定事件类型。 |
| viewArg | IAbstractView | 指定事件的 AbstractView。 |
| detailArg | Int64 | 指定事件的 detail。 |

### 另请参阅

* interface [IAbstractView](../../../aspose.svg.dom.views/iabstractview/)
* class [TimeEvent](../)
* namespace [Aspose.Svg.Events](../../../aspose.svg.events/)
* assembly [Aspose.SVG](../../../)
