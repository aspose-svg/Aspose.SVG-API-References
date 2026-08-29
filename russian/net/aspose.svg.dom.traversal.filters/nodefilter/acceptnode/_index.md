---
title: "NodeFilter.AcceptNode"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод NodeFilter AcceptNode. Проверяет, видим ли указанный узел в логическом представлении TreeWalker или NodeIterator. Эта функция будет вызываться реализацией TreeWalker и NodeIterator; обычно её не вызывают напрямую из пользовательского кода. Тем не менее вы можете сделать это, если хотите использовать тот же фильтр для управления логикой вашего приложения."
type: docs
weight: 10
url: /ru/net/aspose.svg.dom.traversal.filters/nodefilter/acceptnode/
---
## NodeFilter.AcceptNode method

Проверьте, видим ли указанный узел в логическом представлении TreeWalker или NodeIterator. Эта функция будет вызываться реализацией TreeWalker и NodeIterator; обычно она не вызывается напрямую из пользовательского кода. (Хотя вы можете вызвать её, если хотите использовать один и тот же фильтр для управления логикой вашего приложения.)

```csharp
public abstract short AcceptNode(Node n)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| n | Node | узел для проверки, проходит ли он фильтр или нет. |

### Возвращаемое значение

константа, определяющая, принят ли узел, отклонён или пропущен, как указано выше.

### См. также

* class [Node](../../../aspose.svg.dom/node/)
* class [NodeFilter](../)
* namespace [Aspose.Svg.Dom.Traversal.Filters](../../../aspose.svg.dom.traversal.filters/)
* assembly [Aspose.SVG](../../../)
