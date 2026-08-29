---
title: "Node.RemoveChild"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Node RemoveChild. Удаляет дочерний узел из DOM и возвращает удалённый узел."
type: docs
weight: 270
url: /ru/net/aspose.svg.dom/node/removechild/
---
## Node.RemoveChild method

Удаляет дочерний узел из DOM и возвращает удалённый узел.

Примечание: Пока сохраняется ссылка на удалённый дочерний узел, он продолжает существовать в памяти, но больше не является частью DOM. Его можно повторно использовать позже в коде. Если возвращаемое значение `RemoveChild` не сохраняется и нет других ссылок, он будет автоматически удалён из памяти через короткое время.

```csharp
public Node RemoveChild(Node child)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| child | Node | Узел [`Node`](../), который является дочерним узлом, подлежащим удалению из DOM. |

### Возвращаемое значение

В отличие от [`CloneNode`](../clonenode/) возвращаемое значение сохраняет связанные с ним объекты [`EventListener`](../../../aspose.svg.dom.events/ieventlistener/).

### См. также

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
