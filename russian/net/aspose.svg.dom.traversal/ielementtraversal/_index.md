---
title: "Интерфейс IElementTraversal"
second_title: "Aspose.SVG для .NET справочник API"
description: "Интерфейс Aspose.Svg.Dom.Traversal.IElementTraversal. Интерфейс ElementTraversal представляет набор только для чтения атрибутов, позволяющих автору легко перемещаться между элементами в документе. В соответствующих реализациях Element Traversal все объекты, реализующие Element, также должны реализовать интерфейс ElementTraversal."
type: docs
weight: 3230
url: /ru/net/aspose.svg.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

Интерфейс ElementTraversal представляет собой набор только для чтения атрибутов, позволяющих автору легко перемещаться между элементами в документе. В соответствующих реализациях Element Traversal все объекты, реализующие Element, также должны реализовать интерфейс ElementTraversal.

```csharp
public interface IElementTraversal
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ChildElementCount](../../aspose.svg.dom.traversal/ielementtraversal/childelementcount/) { get; } | Возвращает текущее количество узлов-элементов, являющихся дочерними для этого элемента. 0, если у этого элемента нет дочерних узлов типа nodeType 1. |
| [FirstElementChild](../../aspose.svg.dom.traversal/ielementtraversal/firstelementchild/) { get; } | Возвращает первый дочерний узел-элемент этого элемента. null, если у этого элемента нет дочерних элементов. |
| [LastElementChild](../../aspose.svg.dom.traversal/ielementtraversal/lastelementchild/) { get; } | Возвращает последний дочерний элементный узел этого элемента. null, если у этого элемента нет дочерних элементов. |
| [NextElementSibling](../../aspose.svg.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | Возвращает следующий соседний элементный узел этого элемента. null, если у этого элемента нет соседних элементных узлов, идущих после него в дереве документа. |
| [PreviousElementSibling](../../aspose.svg.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | Возвращает предыдущий соседний элементный узел этого элемента. null, если у этого элемента нет соседних элементных узлов, идущих перед ним в дереве документа. |

### См. также

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
