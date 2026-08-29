---
title: "Класс MutationObserverInit"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.Mutations.MutationObserverInit class. Этот класс представляет коллекцию параметров, используемую для настройки MutationObserver."
type: docs
weight: 3120
url: /ru/net/aspose.svg.dom.mutations/mutationobserverinit/
---
## MutationObserverInit class

Этот класс представляет коллекцию параметров, используемую для настройки [`MutationObserver`](../mutationobserver/).

```csharp
public class MutationObserverInit : IDictionary<string, object>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MutationObserverInit](mutationobserverinit/)() | Инициализирует новый экземпляр класса `MutationObserverInit`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AttributeFilter](../../aspose.svg.dom.mutations/mutationobserverinit/attributefilter/) { get; set; } | Устанавливается в список локальных имён атрибутов (без пространства имён), если не все мутации атрибутов нужно наблюдать, и параметр attributes установлен в true или опущен. |
| [AttributeOldValue](../../aspose.svg.dom.mutations/mutationobserverinit/attributeoldvalue/) { get; set; } | Устанавливается в true, если attributes установлен в true или опущен, и значение атрибута цели до мутации должно быть записано. |
| [Attributes](../../aspose.svg.dom.mutations/mutationobserverinit/attributes/) { get; set; } | Установите значение true, если необходимо наблюдать за изменениями атрибутов цели. Может быть опущено, если указаны attributeOldValue и/или attributeFilter. |
| [CharacterData](../../aspose.svg.dom.mutations/mutationobserverinit/characterdata/) { get; set; } | Установите значение true, если необходимо наблюдать за изменениями данных цели. Может быть опущено, если указано characterDataOldValue. |
| [CharacterDataOldValue](../../aspose.svg.dom.mutations/mutationobserverinit/characterdataoldvalue/) { get; set; } | Установите значение true, если characterData установлено в true или опущено, и необходимо записать данные цели до изменения. |
| [ChildList](../../aspose.svg.dom.mutations/mutationobserverinit/childlist/) { get; set; } | Установите значение true, если необходимо наблюдать за изменениями дочерних элементов цели. |
| [Count](../../aspose.svg.dom.mutations/mutationobserverinit/count/) { get; } | Возвращает количество пар ключ/значение, содержащихся в коллекции `MutationObserverInit`. |
| [IsReadOnly](../../aspose.svg.dom.mutations/mutationobserverinit/isreadonly/) { get; } | Определяет, является ли коллекция `MutationObserverInit` изменяемой. |
| [Item](../../aspose.svg.dom.mutations/mutationobserverinit/item/) { get; set; } | Получает или задает элемент с указанным ключом. |
| [Keys](../../aspose.svg.dom.mutations/mutationobserverinit/keys/) { get; } | Получает коллекцию, содержащую ключи из коллекции `MutationObserverInit`. |
| [Subtree](../../aspose.svg.dom.mutations/mutationobserverinit/subtree/) { get; set; } | Установите значение true, если необходимо наблюдать за изменениями не только цели, но и её потомков. |
| [Values](../../aspose.svg.dom.mutations/mutationobserverinit/values/) { get; } | Получает коллекцию, содержащую значения из коллекции `MutationObserverInit`. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.svg.dom.mutations/mutationobserverinit/add/#add)(*KeyValuePair&lt;string, object&gt;*) | Добавляет элемент в коллекцию `MutationObserverInit`. |
| [Add](../../aspose.svg.dom.mutations/mutationobserverinit/add/#add_1)(*string, object*) | Добавляет указанный ключ и значение в коллекцию `MutationObserverInit`. |
| [Clear](../../aspose.svg.dom.mutations/mutationobserverinit/clear/)() | Удаляет все элементы из коллекции `MutationObserverInit`. |
| [Contains](../../aspose.svg.dom.mutations/mutationobserverinit/contains/)(*KeyValuePair&lt;string, object&gt;*) | Определяет, содержит ли `MutationObserverInit` указанную пару ключ/значение. |
| [ContainsKey](../../aspose.svg.dom.mutations/mutationobserverinit/containskey/)(*string*) | Определяет, содержит ли коллекция `MutationObserverInit` указанный ключ. |
| [CopyTo](../../aspose.svg.dom.mutations/mutationobserverinit/copyto/)(*KeyValuePair&lt;string, object&gt;[], int*) | Копирует элементы `MutationObserverInit` в существующий одномерный массив, начиная с указанного индекса массива. |
| [GetEnumerator](../../aspose.svg.dom.mutations/mutationobserverinit/getenumerator/)() | Возвращает перечислитель, который перебирает элементы `MutationObserverInit`. |
| [Remove](../../aspose.svg.dom.mutations/mutationobserverinit/remove/#remove)(*KeyValuePair&lt;string, object&gt;*) | Удаляет указанную пару ключ/значение из коллекции `MutationObserverInit`. |
| [Remove](../../aspose.svg.dom.mutations/mutationobserverinit/remove/#remove_1)(*string*) | Удаляет значение, связанное с указанным ключом, из коллекции `MutationObserverInit`. |
| [TryGetValue](../../aspose.svg.dom.mutations/mutationobserverinit/trygetvalue/)(*string, out object*) | Получает значение, связанное с указанным ключом. |

### См. также

* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)
