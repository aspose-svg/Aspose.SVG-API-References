---
title: "Класс MutationRecord"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.Mutations.MutationRecord class. MutationRecord представляет отдельную мутацию DOM. Это объект, который передаётся в MutationObservers MutationCallback"
type: docs
weight: 3130
url: /ru/net/aspose.svg.dom.mutations/mutationrecord/
---
## MutationRecord class

MutationRecord представляет отдельную мутацию DOM. Это объект, который передаётся в [`MutationObserver`](../mutationobserver/)`'s [`MutationCallback`](../mutationcallback/).

```csharp
public class MutationRecord : DOMObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AddedNodes](../../aspose.svg.dom.mutations/mutationrecord/addednodes/) { get; } | Верните добавленные узлы. |
| [AttributeName](../../aspose.svg.dom.mutations/mutationrecord/attributename/) { get; } | Возвращает локальное имя изменённого атрибута, иначе null. |
| [AttributeNamespace](../../aspose.svg.dom.mutations/mutationrecord/attributenamespace/) { get; } | Возвращает пространство имён изменённого атрибута, иначе null. |
| [NextSibling](../../aspose.svg.dom.mutations/mutationrecord/nextsibling/) { get; } | Верните следующий соседний узел добавленных или удалённых узлов, либо null. |
| [OldValue](../../aspose.svg.dom.mutations/mutationrecord/oldvalue/) { get; } | Возвращаемое значение зависит от типа. Для "attributes" это значение изменённого атрибута до изменения. Для "characterData" это данные изменённого узла до изменения. Для "childList" это null. |
| [PreviousSibling](../../aspose.svg.dom.mutations/mutationrecord/previoussibling/) { get; } | Возвращает предыдущий соседний узел добавленных или удалённых узлов, либо null. |
| [RemovedNodes](../../aspose.svg.dom.mutations/mutationrecord/removednodes/) { get; } | Верните удалённые узлы. |
| [Target](../../aspose.svg.dom.mutations/mutationrecord/target/) { get; } | Возвращает узел, затронутый мутацией, в зависимости от типа. Для "attributes" это элемент, у которого изменился атрибут. Для "characterData" это узел CharacterData. Для "childList" это узел, у которого изменились дочерние элементы. |
| [Type](../../aspose.svg.dom.mutations/mutationrecord/type/) { get; } | Возвращает "attributes", если это была мутация атрибута, "characterData", если это была мутация узла CharacterData, и "childList", если это была мутация дерева узлов. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |

### См. также

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)
