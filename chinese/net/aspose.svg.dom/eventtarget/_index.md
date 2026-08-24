---
title: "EventTarget 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.EventTarget 类。EventTarget 接口由所有支持 DOM 事件模型的实现中的节点实现。因此，可以通过在 Node 接口的实例上使用特定绑定的强制转换方法来获取此接口。该接口允许在 EventTarget 上注册和移除事件监听器，并将事件分派给该 IEventTarget。"
type: docs
weight: 2870
url: /zh/net/aspose.svg.dom/eventtarget/
---
## EventTarget class

`EventTarget` 接口由所有支持 DOM 事件模型的实现中的节点实现。因此，可以通过在 Node 接口的实例上使用特定绑定的强制转换方法来获取此接口。该接口允许在 `EventTarget` 上注册和移除事件监听器，并将事件分派给该 [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/)。

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EventTarget](eventtarget/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/#addeventlistener_1)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 设置一个函数，当指定事件被传递到目标时将被调用。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/#addeventlistener)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 设置一个函数，当指定事件被传递到目标时将被调用。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/#addeventlistener_2)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 设置一个函数，当指定事件被传递到目标时将被调用。 |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | 在指定的 [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) 上分派事件（同步），按适当顺序调用受影响的 EventListeners。正常的事件处理规则（包括捕获阶段和可选的冒泡阶段）同样适用于使用 [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/) 手动分派的事件。 |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | 执行应用程序定义的任务，以释放、清理或重置非托管资源。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 此方法允许从事件目标移除事件监听器。如果在 `EventTarget` 处理事件时移除了 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)，则该监听器不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/#removeeventlistener)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 此方法允许从事件目标移除事件监听器。如果在 `EventTarget` 处理事件时移除了 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)，则该监听器不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 此方法允许从事件目标移除事件监听器。如果在 `EventTarget` 处理事件时移除了 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)，则该监听器不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |

### 另请参阅

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
