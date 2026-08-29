---
title: "Класс HTMLCollection"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Collections.HTMLCollection. HTMLCollection представляет собой обобщённую коллекцию элементов Element"
type: docs
weight: 2010
url: /ru/net/aspose.svg.collections/htmlcollection/
---
## HTMLCollection class

`HTMLCollection` представляет собой обобщённую коллекцию [`Element`](../../aspose.svg.dom/element/).

```csharp
public abstract class HTMLCollection : DOMObject, IEnumerable<Element>
```

## Свойства

| Имя | Описание |
| --- | --- |
| abstract [Item](../../aspose.svg.collections/htmlcollection/item/) { get; } | Возвращает элемент с индексом index в коллекции. Если index больше или равен количеству узлов в списке, возвращается null. |
| abstract [Length](../../aspose.svg.collections/htmlcollection/length/) { get; } | Количество узлов в списке. |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [GetEnumerator](../../aspose.svg.collections/htmlcollection/getenumerator/)() | Получает перечислитель. |
| override [GetPlatformType](../../aspose.svg.collections/htmlcollection/getplatformtype/)() | Этот метод используется для получения типа объекта ECMAScript. |
| [NamedItem](../../aspose.svg.collections/htmlcollection/nameditem/)(*string*) | Возвращает элемент в коллекции, соответствующий указанному имени. |

### См. также

* class [DOMObject](../../aspose.svg.dom/domobject/)
* class [Element](../../aspose.svg.dom/element/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
