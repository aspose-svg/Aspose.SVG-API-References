---
title: "Интерфейс IDocumentTraversal"
second_title: "Aspose.SVG для .NET справочник API"
description: "Интерфейс Aspose.Svg.Dom.Traversal.IDocumentTraversal. DocumentTraversal содержит методы, создающие итераторы и обходчики дерева для обхода узла и его потомков в порядке документа, глубина‑первый обход (pre‑order), который эквивалентен порядку появления открывающих тегов в текстовом представлении документа. В DOM, поддерживающих возможность Traversal, DocumentTraversal будет реализован теми же объектами, которые реализуют интерфейс Document."
type: docs
weight: 3220
url: /ru/net/aspose.svg.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal содержит методы, создающие итераторы и обходчики дерева для обхода узла и его дочерних элементов в порядке документа (обход в глубину, предварительный порядок, который эквивалентен порядку, в котором стартовые теги встречаются в текстовом представлении документа). В DOM, поддерживающих функцию Traversal, DocumentTraversal будет реализован теми же объектами, которые реализуют интерфейс Document.

Смотрите также [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface IDocumentTraversal
```

## Методы

| Имя | Описание |
| --- | --- |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(*[Node](../../aspose.svg.dom/node/)*) | Создаёт новый NodeIterator для поддерева, корнем которого является указанный узел. |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(*[Node](../../aspose.svg.dom/node/), long*) | Создаёт новый NodeIterator для поддерева, корнем которого является указанный узел. |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../inodefilter/)*) | Создаёт новый NodeIterator для поддерева, корнем которого является указанный узел. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(*[Node](../../aspose.svg.dom/node/)*) | Создайте новый TreeWalker над поддеревом, корневым в указанном узле. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(*[Node](../../aspose.svg.dom/node/), long*) | Создайте новый TreeWalker над поддеревом, корневым в указанном узле. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../inodefilter/)*) | Создайте новый TreeWalker над поддеревом, корневым в указанном узле. |

### См. также

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
