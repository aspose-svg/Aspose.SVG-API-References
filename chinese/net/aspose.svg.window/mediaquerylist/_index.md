---
title: "MediaQueryList 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Window.MediaQueryList 类。MediaQueryList 对象存储应用于文档的媒体查询信息，支持对文档状态的即时和事件驱动匹配。参见 CSSOM View Module 规范 https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs
weight: 5960
url: /zh/net/aspose.svg.window/mediaquerylist/
---
## MediaQueryList class

MediaQueryList 对象存储应用于文档的媒体查询信息，支持对文档状态的即时和事件驱动匹配。参见 CSSOM View Module 规范: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```csharp
public class MediaQueryList : EventTarget
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Document](../../aspose.svg.window/mediaquerylist/document/) { get; } | 上下文对象关联的文档。 |
| [Matches](../../aspose.svg.window/mediaquerylist/matches/) { get; } | 一个布尔值，如果文档当前匹配媒体查询列表则返回 true，否则返回 false。 |
| [Media](../../aspose.svg.window/mediaquerylist/media/) { get; } | 表示序列化媒体查询的字符串。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 设置一个函数，当指定事件被传递到目标时将被调用。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 设置一个函数，当指定事件被传递到目标时将被调用。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 设置一个函数，当指定事件被传递到目标时将被调用。 |
| [AddListener](../../aspose.svg.window/mediaquerylist/addlistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 添加 MediaQueryList 匹配状态更改事件监听器。 |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | 在指定的 [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) 上分派事件（同步），按适当顺序调用受影响的 EventListeners。正常的事件处理规则（包括捕获阶段和可选的冒泡阶段）同样适用于使用 [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/) 手动分派的事件。 |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | 执行应用程序定义的任务，以释放、清理或重置非托管资源。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 从 [`EventTarget`](../../aspose.svg.dom/eventtarget/) 中移除，则不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 从 [`EventTarget`](../../aspose.svg.dom/eventtarget/) 中移除，则不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 从 [`EventTarget`](../../aspose.svg.dom/eventtarget/) 中移除，则不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [RemoveListener](../../aspose.svg.window/mediaquerylist/removelistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 移除 MediaQueryList 匹配状态更改事件监听器。 |

## 事件

| 名称 | 描述 |
| --- | --- |
| event [OnChange](../../aspose.svg.window/mediaquerylist/onchange/) | 当匹配状态更改时在 MediaQueryList 上触发的事件。 |

### 另请参阅

* class [EventTarget](../../aspose.svg.dom/eventtarget/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
