---
title: "Интерфейс INodeIterator"
second_title: "Aspose.SVG для .NET справочник API"
description: "Интерфейс Aspose.Svg.Dom.Traversal.INodeIterator. Итераторы используются для последовательного перебора набора узлов, например набора узлов в NodeList, поддерева документа, управляемого определённым Node, результатов запроса или любого другого набора узлов. Набор узлов для перебора определяется реализацией NodeIterator. DOM Level 2 задаёт единственную реализацию NodeIterator для обхода поддерева документа в порядке документа. Экземпляры этих итераторов создаются вызовом DocumentTraversal.createNodeIterator."
type: docs
weight: 3250
url: /ru/net/aspose.svg.dom.traversal/inodeiterator/
---
## INodeIterator interface

Итераторы используются для последовательного перебора набора узлов, например набора узлов в NodeList, поддерева документа, управляемого определённым Node, результатов запроса или любого другого набора узлов. Набор узлов для перебора определяется реализацией NodeIterator. DOM Level 2 определяет единую реализацию NodeIterator для обхода поддерева документа в порядке документа. Экземпляры этих итераторов создаются вызовом DocumentTraversal .createNodeIterator().

Смотрите также [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface INodeIterator : ITraversal
```

## Свойства

| Имя | Описание |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | Значение этого флага определяет, видимы ли дочерние узлы ссылок на сущности для итератора. Если false, они и их потомки будут отклонены. Обратите внимание, что это отклонение имеет приоритет над whatToShow и фильтром. Также отметьте, что в настоящее время это единственная ситуация, когда NodeIterators могут отклонять целое поддерево, а не пропускать отдельные узлы. Чтобы получить представление документа с развернутыми ссылками на сущности и без раскрытия самого узла ссылки на сущность, используйте флаги whatToShow для скрытия узла ссылки на сущность и установите expandEntityReferences в true при создании итератора. Чтобы получить представление документа с узлами ссылок на сущности без их развертывания, используйте флаги whatToShow для отображения узла ссылки на сущность и установите expandEntityReferences в false. |
| [ReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/referencenode/) { get; } | Текущий узел‑ссылка. |

## Методы

| Имя | Описание |
| --- | --- |
| [Detach](../../aspose.svg.dom.traversal/inodeiterator/detach/)() | Отсоединяет NodeIterator от набора, по которому он проходил, освобождая любые вычислительные ресурсы и переводя итератор в состояние INVALID. После вызова detach вызовы nextNode или previousNode вызовут исключение INVALID_STATE_ERR. |
| [NextNode](../../aspose.svg.dom.traversal/inodeiterator/nextnode/)() | Возвращает следующий узел в наборе и перемещает позицию итератора вперёд в наборе. После создания NodeIterator первый вызов nextNode() возвращает первый узел в наборе. |
| [PreviousNode](../../aspose.svg.dom.traversal/inodeiterator/previousnode/)() | Возвращает предыдущий узел в наборе и перемещает позицию NodeIterator назад в наборе. |

### См. также

* interface [ITraversal](../itraversal/)
* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
