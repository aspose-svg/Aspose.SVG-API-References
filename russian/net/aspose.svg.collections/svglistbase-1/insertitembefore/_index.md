---
title: SVGListBase1.InsertItemBefore
second_title: Справочник по Aspose.SVG для .NET API
description: SVGListBase метод. Вставляет новый элемент в список в указанной позиции. Первый элемент номер 0.
type: docs
weight: 90
url: /ru/net/aspose.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Вставляет новый элемент в список в указанной позиции. Первый элемент номер 0.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newItem | T | Элемент, который должен быть вставлен в список. |
| index | UInt64 | Индекс элемента, перед которым должен быть вставлен новый элемент. Первый элемент имеет номер 0. Если индекс равен 0, то новый элемент вставляется в начало списка. Если индекс больше или равен numberOfItems, новый элемент добавляется в конец списка. |

### Возвращаемое значение

Вставленный элемент.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Возникает, когда список нельзя изменить. |

### Смотрите также

* class [SVGListBase&lt;T&gt;](../)
* пространство имен [Aspose.Svg.Collections](../../svglistbase-1/)
* сборка [Aspose.SVG](../../../)


