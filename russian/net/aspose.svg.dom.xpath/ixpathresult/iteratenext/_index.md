---
title: "IXPathResult.IterateNext"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод IXPathResult IterateNext. Перебирает и возвращает следующий узел из набора узлов или null, если узлов больше нет"
type: docs
weight: 80
url: /ru/net/aspose.svg.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

Итерирует и возвращает следующий узел из набора узлов или `null`, если узлов больше нет.

```csharp
public Node IterateNext()
```

### Возвращаемое значение

Возвращает следующий узел.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: вызывается, если `resultType` не имеет тип `UnorderedNodeIterator` или тип `OrderedNodeIterator`. |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: Документ был изменён после того, как результат был возвращён. |

### См. также

* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
