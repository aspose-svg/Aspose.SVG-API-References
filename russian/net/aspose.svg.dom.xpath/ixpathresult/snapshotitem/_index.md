---
title: "IXPathResult.SnapshotItem"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод IXPathResult SnapshotItem. Возвращает элемент с индексом index в коллекции снимков. Если index больше или равен количеству узлов в списке, этот метод возвращает null. В отличие от результата итератора, снимок не становится недействительным, но может не соответствовать текущему документу, если он изменён."
type: docs
weight: 90
url: /ru/net/aspose.svg.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Возвращает `index`‑й элемент в коллекции снимка. Если `index` больше или равен количеству узлов в списке, этот метод возвращает `null`. В отличие от результата итератора, снимок не становится недействительным, но может не соответствовать текущему документу, если он изменён.

```csharp
public Node SnapshotItem(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс в коллекцию снимков. |

### Возвращаемое значение

Узел на позиции `index` в `NodeList`, или `null`, если индекс недействителен.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: вызывается, если `resultType` не имеет тип `UnorderedNodeSnapshot` или тип `OrderedNodeSnapshot`. |

### См. также

* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
