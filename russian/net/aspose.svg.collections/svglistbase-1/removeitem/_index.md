---
title: "SVGListBase-1.RemoveItem"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод RemoveItem класса SVGListBase. Удаляет существующий элемент из списка"
type: docs
weight: 100
url: /ru/net/aspose.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase<T>.RemoveItem method

Удаляет существующий элемент из списка.

```csharp
public T RemoveItem(ulong index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | UInt64 | Индекс элемента, который будет удалён. Первый элемент имеет номер 0. |

### Возвращаемое значение

Удалённый элемент.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Возникает, когда список нельзя изменить. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Возникает, если номер индекса больше или равен numberOfItems. |

### См. также

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
