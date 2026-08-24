---
title: "IEventListener 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Events.IEventListener 接口。IEventListener 接口是处理事件的主要方式。用户实现 IEventListener 接口并使用 AddEventListener 方法在 EventTarget 上注册其监听器。用户在完成使用监听器后，还应从其 EventTarget 中移除 IEventListener。"
type: docs
weight: 2950
url: /zh/net/aspose.svg.dom.events/ieventlistener/
---
## IEventListener interface

`IEventListener` 接口是处理事件的主要方式。用户实现 `IEventListener` 接口并使用 [`EventTarget`](../../aspose.svg.dom/eventtarget/) 上的 [`AddEventListener`](../../aspose.svg.dom/eventtarget/addeventlistener/) 方法注册其监听器。用户在完成使用监听器后，还应从其 [`EventTarget`](../../aspose.svg.dom/eventtarget/) 中移除 `IEventListener`。

```csharp
public interface IEventListener
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [HandleEvent](../../aspose.svg.dom.events/ieventlistener/handleevent/)(*[Event](../event/)*) | 每当发生 `IEventListener` 接口已注册的类型的事件时，都会调用此方法。 |

## 备注

使用 cloneNode 方法复制 Node 时，附加在源 Node 上的事件监听器不会复制到新节点。如果用户希望将相同的事件监听器添加到新创建的副本中，必须手动添加它们。

### 另请参阅

* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
