---
title: "Класс MutationObserver"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.Mutations.MutationObserver class. Объект MutationObserver может использоваться для наблюдения за мутациями дерева Node."
type: docs
weight: 3110
url: /ru/net/aspose.svg.dom.mutations/mutationobserver/
---
## MutationObserver class

Объект `MutationObserver` может использоваться для наблюдения за мутациями дерева [`Node`](../../aspose.svg.dom/node/).

```csharp
public class MutationObserver : DOMObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MutationObserver](mutationobserver/)(*[MutationCallback](../mutationcallback/)*) | Создаёт объект MutationObserver и задаёт его [`MutationCallback`](../mutationcallback/) как callback. Callback вызывается со списком объектов MutationRecord в качестве первого аргумента и созданным объектом MutationObserver в качестве второго аргумента. Он вызывается после того, как узлы, зарегистрированные методом [`Observe`](./observe/), были изменены. |

## Методы

| Имя | Описание |
| --- | --- |
| [Disconnect](../../aspose.svg.dom.mutations/mutationobserver/disconnect/)() | Останавливает наблюдатель от отслеживания любых мутаций. Пока метод observe() не будет вызван снова, callback наблюдателя не будет вызываться. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe)(*[Node](../../aspose.svg.dom/node/)*) | Инструктирует пользовательский агент наблюдать за заданной целью (узлом) и сообщать о любых мутациях в соответствии с критериями, заданными параметром options (объект). Аргумент options позволяет задавать параметры наблюдения за мутациями через члены объекта. |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe_1)(*[Node](../../aspose.svg.dom/node/), [MutationObserverInit](../mutationobserverinit/)*) | Инструктирует пользовательский агент наблюдать за заданной целью (узлом) и сообщать о любых мутациях в соответствии с критериями, заданными параметром options (объект). Аргумент options позволяет задавать параметры наблюдения за мутациями через члены объекта. |
| [TakeRecords](../../aspose.svg.dom.mutations/mutationobserver/takerecords/)() | Метод возвращает копию очереди записей и затем очищает очередь записей. |

### См. также

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)
