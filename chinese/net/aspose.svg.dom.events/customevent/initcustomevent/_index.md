---
title: "CustomEvent.InitCustomEvent"
second_title: "Aspose.SVG for .NET API 参考"
description: "CustomEvent InitCustomEvent 方法。/// InitEvent 方法用于初始化通过 IDocumentEvent 接口创建的 Event 的值"
type: docs
weight: 30
url: /zh/net/aspose.svg.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// 该 [`InitEvent`](../../event/initevent/) 方法用于初始化通过 [`IDocumentEvent`](../../idocumentevent/) 接口创建的 [`Event`](../../event/) 的值。

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 事件类型。 |
| bubbles | Boolean | 如果设置为 `true` [bubbles]。 |
| cancelable | Boolean | 如果设置为 `true` [cancelable]。 |
| detail | 对象 | 自定义数据。 |

## 备注

此方法只能在 Event 通过 [`DispatchEvent`](../../ieventtarget/dispatchevent/) 方法分发之前调用，尽管在该阶段如有必要可以多次调用。如果多次调用，则以最后一次调用为准。如果从 Event 接口的子类调用，则仅修改 initEvent 方法中指定的值，所有其他属性保持不变。

### 另请参阅

* class [CustomEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
