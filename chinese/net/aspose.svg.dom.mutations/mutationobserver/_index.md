---
title: "MutationObserver 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Mutations.MutationObserver 类。MutationObserver 对象可用于观察 Node 树的变更"
type: docs
weight: 3110
url: /zh/net/aspose.svg.dom.mutations/mutationobserver/
---
## MutationObserver class

`MutationObserver` 对象可用于观察 [`Node`](../../aspose.svg.dom/node/) 树的变更。

```csharp
public class MutationObserver : DOMObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MutationObserver](mutationobserver/)(*[MutationCallback](../mutationcallback/)*) | 构造一个 MutationObserver 对象并将其 [`MutationCallback`](../mutationcallback/) 设置为 callback。callback 在第一个参数为 MutationRecord 对象列表、第二个参数为构造的 MutationObserver 对象时被调用。它在使用 [`Observe`](./observe/) 方法注册的节点发生变更后被调用。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Disconnect](../../aspose.svg.dom.mutations/mutationobserver/disconnect/)() | 停止观察者观察任何变更。直到再次调用 observe() 方法，观察者的回调才会被触发。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe)(*[Node](../../aspose.svg.dom/node/)*) | 指示用户代理观察给定的目标（一个节点），并根据 options（一个对象）提供的条件报告任何变更。options 参数允许通过对象成员设置变更观察选项。 |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe_1)(*[Node](../../aspose.svg.dom/node/), [MutationObserverInit](../mutationobserverinit/)*) | 指示用户代理观察给定的目标（一个节点），并根据 options（一个对象）提供的条件报告任何变更。options 参数允许通过对象成员设置变更观察选项。 |
| [TakeRecords](../../aspose.svg.dom.mutations/mutationobserver/takerecords/)() | 该方法返回记录队列的副本，然后清空记录队列。 |

### 另请参阅

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)
