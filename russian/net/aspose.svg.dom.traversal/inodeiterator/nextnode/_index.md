---
title: "INodeIterator.NextNode"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод INodeIterator NextNode. Возвращает следующий узел в наборе и перемещает позицию итератора вперёд в наборе. После создания NodeIterator первый вызов nextNode возвращает первый узел в наборе."
type: docs
weight: 40
url: /ru/net/aspose.svg.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Возвращает следующий узел в наборе и перемещает позицию итератора вперёд в наборе. После создания NodeIterator первый вызов nextNode() возвращает первый узел в наборе.

```csharp
public Node NextNode()
```

### Возвращаемое значение

Следующий узел в наборе, по которому производится итерация, или null, если в этом наборе больше нет элементов.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: Возникает, если этот метод вызывается после вызова метода detach. |

### См. также

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
