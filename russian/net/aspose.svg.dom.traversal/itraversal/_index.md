---
title: "Интерфейс ITraversal"
second_title: "Aspose.SVG для .NET справочник API"
description: "Интерфейс Aspose.Svg.Dom.Traversal.ITraversal. Итераторы используются для прохода по набору узлов, например набору узлов в NodeList, поддереву документа, управляемому определённым Node, результатам запроса или любому другому набору узлов. Набор узлов, по которым будет происходить итерация, определяется реализацией NodeIterator. DOM Level 2 определяет единственную реализацию NodeIterator для обхода документа в порядке следования узлов поддерева. Экземпляры этих итераторов создаются вызовом DocumentTraversal.createNodeIterator"
type: docs
weight: 3260
url: /ru/net/aspose.svg.dom.traversal/itraversal/
---
## ITraversal interface

Итераторы используются для последовательного перебора набора узлов, например набора узлов в NodeList, поддерева документа, управляемого определённым Node, результатов запроса или любого другого набора узлов. Набор узлов для перебора определяется реализацией NodeIterator. DOM Level 2 определяет единую реализацию NodeIterator для обхода поддерева документа в порядке документа. Экземпляры этих итераторов создаются вызовом DocumentTraversal .createNodeIterator().

Смотрите также [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface ITraversal : IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Filter](../../aspose.svg.dom.traversal/itraversal/filter/) { get; } | NodeFilter, используемый для фильтрации узлов. |
| [Root](../../aspose.svg.dom.traversal/itraversal/root/) { get; } | Корневой узел NodeIterator, указанный при его создании. |
| [WhatToShow](../../aspose.svg.dom.traversal/itraversal/whattoshow/) { get; } | Этот атрибут определяет, какие типы узлов представлены через итератор. Доступный набор констант определён в интерфейсе NodeFilter. Узлы, не принятые whatToShow, будут пропущены, но их дочерние элементы могут всё равно учитываться. Обратите внимание, что такое пропускание имеет приоритет над фильтром, если он присутствует. |

### См. также

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
