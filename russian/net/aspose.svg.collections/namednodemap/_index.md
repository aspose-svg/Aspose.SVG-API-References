---
title: "Класс NamedNodeMap"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Collections.NamedNodeMap. Представляет коллекции атрибутов, к которым можно получить доступ по имени."
type: docs
weight: 2020
url: /ru/net/aspose.svg.collections/namednodemap/
---
## NamedNodeMap class

Представляет коллекции атрибутов, к которым можно получить доступ по имени.

```csharp
public class NamedNodeMap : DOMObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Item](../../aspose.svg.collections/namednodemap/item/) { get; } | Возвращает элемент карты с индексом index. Если индекс больше или равен количеству узлов в этой карте, возвращается null. (2 индексатора) |
| [Length](../../aspose.svg.collections/namednodemap/length/) { get; } | Количество узлов в этой карте. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetNamedItem](../../aspose.svg.collections/namednodemap/getnameditem/)(*string*) | Получает узел, указанный по имени. |
| [GetNamedItemNS](../../aspose.svg.collections/namednodemap/getnameditemns/)(*string, string*) | Получает узел, указанный по локальному имени и URI пространства имён. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [RemoveNamedItem](../../aspose.svg.collections/namednodemap/removenameditem/)(*string*) | Удаляет узел, указанный по имени. |
| [RemoveNamedItemNS](../../aspose.svg.collections/namednodemap/removenameditemns/)(*string, string*) | Удаляет узел, указанный по локальному имени и URI пространства имён. |
| [SetNamedItem](../../aspose.svg.collections/namednodemap/setnameditem/)(*[Attr](../../aspose.svg.dom/attr/)*) | Добавляет узел, используя его атрибут nodeName. Если узел с таким именем уже присутствует в этой карте, он заменяется новым. Замена узла самим собой не оказывает эффекта. |
| [SetNamedItemNS](../../aspose.svg.collections/namednodemap/setnameditemns/)(*[Attr](../../aspose.svg.dom/attr/)*) | Добавляет узел, используя его namespaceURI и localName. Если узел с таким URI пространства имен и таким локальным именем уже присутствует в этой карте, он заменяется новым. Замена узла самим собой не оказывает эффекта. |

### См. также

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
