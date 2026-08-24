---
title: "IEventTarget 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Events.IEventTarget 接口。EventTarget 接口由所有支持 DOM 事件模型的实现中的节点实现。因此，可以通过在 Node 接口的实例上使用特定绑定的强制转换方法来获取此接口。该接口允许在 EventTarget 上注册和移除事件监听器，并将事件分派给该 IEventTarget。"
type: docs
weight: 2960
url: /zh/net/aspose.svg.dom.events/ieventtarget/
---
## IEventTarget interface

[`EventTarget`](../../aspose.svg.dom/eventtarget/) 接口由所有支持 DOM 事件模型的实现中的节点实现。因此，可以通过在 Node 接口的实例上使用特定绑定的强制转换方法来获取此接口。该接口允许在 [`EventTarget`](../../aspose.svg.dom/eventtarget/) 上注册和移除事件监听器，并将事件分派给该 `IEventTarget`。

```csharp
public interface IEventTarget
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom.events/ieventtarget/addeventlistener/#addeventlistener)(*string, [IEventListener](../ieventlistener/)*) | 此方法允许在事件目标上注册事件监听器。 |
| [AddEventListener](../../aspose.svg.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | 此方法允许在事件目标上注册事件监听器。 |
| [DispatchEvent](../../aspose.svg.dom.events/ieventtarget/dispatchevent/)(*[Event](../event/)*) | 此方法允许将事件分派到实现的事件模型中。 |
| [RemoveEventListener](../../aspose.svg.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(*string, [IEventListener](../ieventlistener/)*) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从 [`EventTarget`](../../aspose.svg.dom/eventtarget/) 中移除 [`IEventListener`](../ieventlistener/)，则该监听器不会在当前操作中被触发。事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.svg.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从 [`EventTarget`](../../aspose.svg.dom/eventtarget/) 中移除 [`IEventListener`](../ieventlistener/)，则该监听器不会在当前操作中被触发。事件监听器在被移除后永远不会被调用。 |

### 另请参阅

* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
