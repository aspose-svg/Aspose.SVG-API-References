---
title: "IParentNode интерфейс"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.IParentNode интерфейс. Определяет интерфейс IParentNode, который реализуется любыми возможными родителями"
type: docs
weight: 3080
url: /ru/net/aspose.svg.dom/iparentnode/
---
## IParentNode interface

Определяет интерфейс `IParentNode`, который реализуется любыми возможными родителями.

```csharp
public interface IParentNode : IElementTraversal
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ChildElementCount](../../aspose.svg.dom/iparentnode/childelementcount/) { get; } | Атрибут childElementCount должен возвращать количество дочерних элементов контекстного объекта, которые являются элементами. |
| [Children](../../aspose.svg.dom/iparentnode/children/) { get; } | Возвращает дочерние элементы. |
| [FirstElementChild](../../aspose.svg.dom/iparentnode/firstelementchild/) { get; } | Возвращает первый дочерний узел, который является элементом, иначе null. |
| [LastElementChild](../../aspose.svg.dom/iparentnode/lastelementchild/) { get; } | Возвращает последний дочерний узел, который является элементом, иначе null. |

## Методы

| Имя | Описание |
| --- | --- |
| [QuerySelector](../../aspose.svg.dom/iparentnode/queryselector/)(*string*) | Возвращает первый элемент, который является потомком узла и соответствует селекторам. |
| [QuerySelectorAll](../../aspose.svg.dom/iparentnode/queryselectorall/)(*string*) | Возвращает все элементные потомки узла, соответствующие селекторам. |

### См. также

* interface [IElementTraversal](../../aspose.svg.dom.traversal/ielementtraversal/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
