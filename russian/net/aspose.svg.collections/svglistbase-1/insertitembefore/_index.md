---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод InsertItemBefore класса SVGListBase. Вставляет новый элемент в список в указанную позицию. Первый элемент имеет номер 0"
type: docs
weight: 90
url: /ru/net/aspose.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase<T>.InsertItemBefore method

Вставляет новый элемент в список в указанную позицию. Первый элемент имеет номер 0.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newItem | T | Элемент, который будет вставлен в список. |
| index | UInt64 | Индекс элемента, перед которым будет вставлен новый элемент. Первый элемент имеет номер 0. Если индекс равен 0, новый элемент вставляется в начало списка. Если индекс больше или равен numberOfItems, новый элемент добавляется в конец списка. |

### Возвращаемое значение

Вставленный элемент.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Возникает, когда список нельзя изменить. |

### См. также

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
