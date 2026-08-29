---
title: "SVGListBase-1.GetItem"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод GetItem класса SVGListBase. Возвращает указанный элемент из списка"
type: docs
weight: 70
url: /ru/net/aspose.svg.collections/svglistbase-1/getitem/
---
## SVGListBase<T>.GetItem method

Возвращает указанный элемент из списка.

```csharp
public T GetItem(ulong index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | UInt64 | Индекс элемента из списка, который будет возвращён. Первый элемент имеет номер 0. |

### Возвращаемое значение

Выбранный элемент.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Возникает, если номер индекса больше или равен numberOfItems. |

### См. также

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
