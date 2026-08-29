---
title: "SVGListBase-1.Item"
second_title: "Aspose.SVG для .NET справочник API"
description: "Свойство Item класса SVGListBase. Возвращает элемент с индексом в списке"
type: docs
weight: 10
url: /ru/net/aspose.svg.collections/svglistbase-1/item/
---
## SVGListBase<T> indexer

Возвращает элемент с индексом index в списке.

```csharp
public T this[ulong index] { get; set; }
```

| Параметр | Описание |
| --- | --- |
| index | Индекс в списке. |

### Возвращаемое значение

Сохранённый объект на позиции с индексом в списке.

### Property Value

Тип элемента, хранящегося в списке.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Возникает, когда список нельзя изменить. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Возникает, если номер индекса больше или равен numberOfItems. |

### См. также

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
