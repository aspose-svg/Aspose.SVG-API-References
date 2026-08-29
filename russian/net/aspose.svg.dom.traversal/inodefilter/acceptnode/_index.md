---
title: "INodeFilter.AcceptNode"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод AcceptNode интерфейса INodeFilter. Проверяет, виден ли указанный узел в логическом представлении TreeWalker или NodeIterator. Эта функция вызывается реализацией TreeWalker и NodeIterator и обычно не вызывается напрямую из пользовательского кода. Однако вы можете вызвать её, если хотите использовать тот же фильтр для управления логикой вашего приложения."
type: docs
weight: 10
url: /ru/net/aspose.svg.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

Проверьте, видим ли указанный узел в логическом представлении TreeWalker или NodeIterator. Эта функция будет вызываться реализацией TreeWalker и NodeIterator; обычно она не вызывается напрямую из пользовательского кода. (Хотя вы можете вызвать её, если хотите использовать один и тот же фильтр для управления логикой вашего приложения.)

```csharp
public short AcceptNode(Node n)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| n | Node | узел для проверки, проходит ли он фильтр или нет. |

### Возвращаемое значение

константа, определяющая, принят ли узел, отклонён или пропущен, как указано выше.

### См. также

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
