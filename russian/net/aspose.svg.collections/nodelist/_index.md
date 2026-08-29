---
title: "Класс NodeList"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Collections.NodeList. NodeList предоставляет абстракцию упорядоченной коллекции узлов без определения или ограничения того, как эта коллекция реализована"
type: docs
weight: 2030
url: /ru/net/aspose.svg.collections/nodelist/
---
## NodeList class

NodeList предоставляет абстракцию упорядоченной коллекции узлов, не определяя и не ограничивая способ реализации этой коллекции.

```csharp
public abstract class NodeList : DOMObject, IEnumerable<Node>
```

## Свойства

| Имя | Описание |
| --- | --- |
| abstract [Item](../../aspose.svg.collections/nodelist/item/) { get; } | Метод возвращает элемент с индексом index в коллекции. Если index больше или равен количеству узлов в списке, возвращается null. |
| abstract [Length](../../aspose.svg.collections/nodelist/length/) { get; } | Количество узлов в списке. |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [GetEnumerator](../../aspose.svg.collections/nodelist/getenumerator/)() | Возвращает перечислитель, который проходит по коллекции. |
| override [GetPlatformType](../../aspose.svg.collections/nodelist/getplatformtype/)() | Этот метод используется для получения типа объекта ECMAScript. |

### См. также

* class [DOMObject](../../aspose.svg.dom/domobject/)
* class [Node](../../aspose.svg.dom/node/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
