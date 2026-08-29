---
title: "SVGListBase-1.ReplaceItem"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод ReplaceItem у SVGListBase. Заменяет существующий элемент в списке новым элементом"
type: docs
weight: 110
url: /ru/net/aspose.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase<T>.ReplaceItem method

Заменяет существующий элемент в списке новым элементом.

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newItem | T | Элемент, который будет вставлен в список. |
| index | UInt64 | Индекс элемента, который будет заменён. Первый элемент имеет номер 0. |

### Возвращаемое значение

Вставленный элемент.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Возникает, когда список нельзя изменить. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Возникает, если номер индекса больше или равен numberOfItems. |

### См. также

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
