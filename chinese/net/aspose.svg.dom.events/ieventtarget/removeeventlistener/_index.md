---
title: "IEventTarget.RemoveEventListener"
second_title: "Aspose.SVG for .NET API 参考"
description: "IEventTarget RemoveEventListener 方法。此方法允许从事件目标中移除事件监听器。如果在处理事件时从 EventTarget 中移除 IEventListener，则该监听器不会被当前操作触发。事件监听器在被移除后永远不会被调用"
type: docs
weight: 30
url: /zh/net/aspose.svg.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(*string, [IEventListener](../../ieventlistener/)*) {#removeeventlistener}

此方法允许从事件目标中移除事件监听器。如果在处理事件时从 [`IEventListener`](../../ieventlistener/) 中移除 [`EventTarget`](../../../aspose.svg.dom/eventtarget/)，则该监听器不会被当前操作触发。事件监听器在被移除后永远不会被调用。

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 指定被移除的 [`IEventListener`](../../ieventlistener/) 的事件类型。 |
| listener | IEventListener | [`IEventListener`](../../ieventlistener/) 参数指示要移除的 [`IEventListener`](../../ieventlistener/)。 |

### 另请参阅

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../ieventlistener/), bool*) {#removeeventlistener_1}

此方法允许从事件目标中移除事件监听器。如果在处理事件时从 [`IEventListener`](../../ieventlistener/) 中移除 [`EventTarget`](../../../aspose.svg.dom/eventtarget/)，则该监听器不会被当前操作触发。事件监听器在被移除后永远不会被调用。

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 指定被移除的 [`IEventListener`](../../ieventlistener/) 的事件类型。 |
| listener | IEventListener | [`IEventListener`](../../ieventlistener/) 参数指示要移除的 [`IEventListener`](../../ieventlistener/)。 |
| useCapture | Boolean | 指定被移除的 EventListener 是否已注册为捕获监听器。如果同一监听器注册了两次，一次为捕获模式，一次为非捕获模式，则必须分别移除。移除捕获监听器不会影响同一监听器的非捕获版本，反之亦然。 |

### 另请参阅

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
