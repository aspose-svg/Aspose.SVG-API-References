---
title: "IDocumentEvent.CreateEvent"
second_title: "Aspose.SVG for .NET API 参考"
description: "IDocumentEvent CreateEvent 方法。创建实现支持类型的事件。"
type: docs
weight: 10
url: /zh/net/aspose.svg.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

创建一个实现支持类型的 [`Event`](../../event/)。

```csharp
public Event CreateEvent(string eventType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| eventType | String | `eventType` 参数指定要创建的 [`Event`](../../event/) 接口的类型。如果实现支持指定的 [`Event`](../../event/) 接口，则此方法将返回一个请求的接口类型的新 [`Event`](../../event/)。如果要通过 [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) 方法分发该 [`Event`](../../event/)，则在创建后必须调用相应的 [`InitEvent`](../../event/initevent/) 方法以初始化该 [`Event`](../../event/) 的值。 |

### 返回值

新创建的 [`Event`](../../event/)

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR：如果实现不支持请求的 [`Event`](../../event/) 接口类型，则抛出此错误。 |

### 另请参阅

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
