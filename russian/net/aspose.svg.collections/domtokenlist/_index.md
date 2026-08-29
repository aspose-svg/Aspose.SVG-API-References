---
title: "Класс DOMTokenList"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Collections.DOMTokenList. Класс DOMTokenList представляет набор токенов, разделённых пробелами. Он индексируется, начиная с 0, как объекты массива JavaScript. DOMTokenList всегда чувствителен к регистру."
type: docs
weight: 2000
url: /ru/net/aspose.svg.collections/domtokenlist/
---
## DOMTokenList class

Класс DOMTokenList представляет набор токенов, разделённых пробелами. Он индексируется, начиная с 0, как объекты массива JavaScript. DOMTokenList всегда чувствителен к регистру.

```csharp
public class DOMTokenList : DOMObject, IEnumerable<string>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Item](../../aspose.svg.collections/domtokenlist/item/) { get; } | Возвращает элемент списка по его индексу или null, если индекс больше или равен длине списка. |
| [Length](../../aspose.svg.collections/domtokenlist/length/) { get; } | Возвращает ulong, представляющий количество токенов, хранящихся в этом списке. |
| [Value](../../aspose.svg.collections/domtokenlist/value/) { get; set; } | Получает или задает значение соответствующего атрибута. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.svg.collections/domtokenlist/add/)(*params string[]*) | Добавляет указанные токен(ы) в список. |
| [Contains](../../aspose.svg.collections/domtokenlist/contains/)(*string*) | Возвращает true, если список содержит указанный токен, иначе false. |
| [GetEnumerator](../../aspose.svg.collections/domtokenlist/getenumerator/)() | Возвращает перечислитель, который проходит по коллекции. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [Remove](../../aspose.svg.collections/domtokenlist/remove/)(*params string[]*) | Удаляет указанные токен(ы) из списка. |
| [Replace](../../aspose.svg.collections/domtokenlist/replace/)(*string, string*) | Заменяет существующий токен новым токеном. Не делает ничего, если первый токен не существует. |
| [Supports](../../aspose.svg.collections/domtokenlist/supports/)(*string*) | Возвращает true, если данный токен находится в поддерживаемых токенах связанного атрибута. |
| [Toggle](../../aspose.svg.collections/domtokenlist/toggle/#toggle)(*string*) | Удаляет токен из списка, если он существует, или добавляет токен в список, если его нет. |
| [Toggle](../../aspose.svg.collections/domtokenlist/toggle/#toggle_1)(*string, bool*) | Удаляет токен из списка, если он существует, или добавляет токен в список, если его нет. |

### См. также

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
