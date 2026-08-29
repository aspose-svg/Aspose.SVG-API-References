---
title: "IXPathResult интерфейс"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.XPath.IXPathResult интерфейс. Интерфейс XPathResult представляет результат оценки XPath‑выражения версии 1.0 в контексте конкретного узла. Поскольку оценка XPath‑выражения может давать различные типы результатов, этот объект позволяет обнаруживать и управлять типом и значением результата."
type: docs
weight: 3350
url: /ru/net/aspose.svg.dom.xpath/ixpathresult/
---
## IXPathResult interface

Интерфейс `XPathResult` представляет результат оценки XPath‑выражения 1.0 в контексте конкретного узла. Поскольку оценка XPath‑выражения может приводить к различным типам результатов, этот объект позволяет обнаруживать и манипулировать типом и значением результата.

```csharp
public interface IXPathResult
```

## Свойства

| Имя | Описание |
| --- | --- |
| [BooleanValue](../../aspose.svg.dom.xpath/ixpathresult/booleanvalue/) { get; } | Значение этого логического результата. |
| [InvalidIteratorState](../../aspose.svg.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | Указывает, что итератор стал недействительным. Истина, если `resultType` имеет тип `UnorderedNodeIterator` или `OrderedNodeIterator` и документ был изменён с момента возврата этого результата. |
| [NumberValue](../../aspose.svg.dom.xpath/ixpathresult/numbervalue/) { get; } | Значение этого числового результата. |
| [ResultType](../../aspose.svg.dom.xpath/ixpathresult/resulttype/) { get; } | Код, представляющий тип этого результата, как определено в http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult enum [`XPathResultType`](../xpathresulttype/). |
| [SingleNodeValue](../../aspose.svg.dom.xpath/ixpathresult/singlenodevalue/) { get; } | Значение этого результата единственного узла, которое может быть `null`. |
| [SnapshotLength](../../aspose.svg.dom.xpath/ixpathresult/snapshotlength/) { get; } | Количество узлов в снимке результата. Допустимые значения индексов snapshotItem — от `0` до `snapshotLength-1` включительно. |
| [StringValue](../../aspose.svg.dom.xpath/ixpathresult/stringvalue/) { get; } | Значение этого строкового результата. |

## Методы

| Имя | Описание |
| --- | --- |
| [IterateNext](../../aspose.svg.dom.xpath/ixpathresult/iteratenext/)() | Итерирует и возвращает следующий узел из набора узлов или `null`, если узлов больше нет. |
| [SnapshotItem](../../aspose.svg.dom.xpath/ixpathresult/snapshotitem/)(*int*) | Возвращает `index`‑й элемент в коллекции снимка. Если `index` больше или равен количеству узлов в списке, этот метод возвращает `null`. В отличие от результата итератора, снимок не становится недействительным, но может не соответствовать текущему документу, если он изменён. |

### См. также

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
