---
title: IEventTarget.AddEventListener
second_title: Aspose.SVG for .NET API 参考
description: IEventTarget 方法. 此方法允许在事件目标上注册事件侦听器
type: docs
weight: 10
url: /zh/net/aspose.svg.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(string, IEventListener) {#addeventlistener}

此方法允许在事件目标上注册事件侦听器。

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 用户注册的事件类型 |
| listener | IEventListener | 采用用户实现的接口，其中包含事件发生时要调用的方法。 |

### 评论

如果一个[`IEventListener`](../../ieventlistener/)被添加到一个[`EventTarget`](../../../aspose.svg.dom/eventtarget/)当它正在处理事件时，它不会被当前操作触发 ，但可能会在事件流的后期触发，例如冒泡阶段。

如果多个相同的事件监听器注册在同一个[`EventTarget`](../../../aspose.svg.dom/eventtarget/)使用相同的参数，重复的实例将被丢弃。 它们不会导致[`IEventListener`](../../ieventlistener/)被调用两次，因为它们被丢弃，所以不需要用 the 删除它们[`RemoveEventListener`](../removeeventlistener/) 方法.

### 也可以看看

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* 命名空间 [Aspose.Svg.Dom.Events](../../ieventtarget/)
* 部件 [Aspose.SVG](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_1}

此方法允许在事件目标上注册事件侦听器。

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 用户注册的事件类型 |
| listener | IEventListener | 采用用户实现的接口，其中包含事件发生时要调用的方法。 |
| useCapture | Boolean | 如果为true，useCapture表示用户希望发起捕获。 发起捕获后，指定类型的所有事件将被派发到registered [`IEventListener`](../../ieventlistener/) 在被分派到树中它们下面的任何事件目标之前。 通过树向上冒泡的事件不会触发[`IEventListener`](../../ieventlistener/)指定使用捕获。 |

### 评论

如果一个[`IEventListener`](../../ieventlistener/)被添加到一个[`EventTarget`](../../../aspose.svg.dom/eventtarget/)当它正在处理事件时，它不会被当前操作触发 ，但可能会在事件流的后期触发，例如冒泡阶段。

如果多个相同的事件监听器注册在同一个[`EventTarget`](../../../aspose.svg.dom/eventtarget/)使用相同的参数，重复的实例将被丢弃。 它们不会导致[`IEventListener`](../../ieventlistener/)被调用两次，因为它们被丢弃，所以不需要用 the 删除它们[`RemoveEventListener`](../removeeventlistener/) 方法.

### 也可以看看

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* 命名空间 [Aspose.Svg.Dom.Events](../../ieventtarget/)
* 部件 [Aspose.SVG](../../../)


