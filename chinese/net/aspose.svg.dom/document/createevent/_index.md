---
title: "Document.CreateEvent"
second_title: "Aspose.SVG for .NET API 参考"
description: "Document CreateEvent 方法。创建实现支持类型的 Event。"
type: docs
weight: 880
url: /zh/net/aspose.svg.dom/document/createevent/
---
## Document.CreateEvent method

创建一个实现支持类型的 [`Event`](../../../aspose.svg.dom.events/event/)。

```csharp
public Event CreateEvent(string eventType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| eventType | String | eventType 参数指定要创建的 [`Event`](../../../aspose.svg.dom.events/event/) 接口的类型。如果实现支持指定的 [`Event`](../../../aspose.svg.dom.events/event/) 接口，则此方法将返回一个新的请求的接口类型的 [`Event`](../../../aspose.svg.dom.events/event/)。如果要通过 [`DispatchEvent`](../../../aspose.svg.dom.events/ieventtarget/dispatchevent/) 方法分派该 [`Event`](../../../aspose.svg.dom.events/event/)，则必须在创建后调用相应的 [`InitEvent`](../../../aspose.svg.dom.events/event/initevent/) 方法，以初始化该 [`Event`](../../../aspose.svg.dom.events/event/) 的值。 |

### 返回值

新创建的 [`Event`](../../../aspose.svg.dom.events/event/)

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: 如果实现不支持请求的 [`Event`](../../../aspose.svg.dom.events/event/) 接口类型，则会抛出此错误 |

### 另请参阅

* class [Event](../../../aspose.svg.dom.events/event/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
