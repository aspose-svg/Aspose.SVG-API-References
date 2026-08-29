---
title: "Интерфейс IMediaList"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.Css.IMediaList interface. Интерфейс MediaList предоставляет абстракцию упорядоченной коллекции носителей без определения или ограничения того, как эта коллекция реализована. Пустой список эквивалентен списку, содержащему все носители."
type: docs
weight: 2730
url: /ru/net/aspose.svg.dom.css/imedialist/
---
## IMediaList interface

Интерфейс MediaList предоставляет абстракцию упорядоченной коллекции носителей, не определяя и не ограничивая способ реализации этой коллекции. Пустой список эквивалентен списку, содержащему носитель "all".

```csharp
public interface IMediaList : IEnumerable<string>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Item](../../aspose.svg.dom.css/imedialist/item/) { get; } | Возвращает элемент с указанным индексом в списке. Если индекс больше или равен количеству носителей в списке, возвращается null. Индекс носителя. |
| [Length](../../aspose.svg.dom.css/imedialist/length/) { get; } | Количество носителей в списке. Диапазон допустимых индексов носителей от 0 до length‑1 включительно. |
| [MediaText](../../aspose.svg.dom.css/imedialist/mediatext/) { get; } | Разбираемое текстовое представление списка носителей. Это список носителей, разделённых запятыми. |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendMedium](../../aspose.svg.dom.css/imedialist/appendmedium/)(*string*) | Добавляет носитель newMedium в конец списка. Если newMedium уже используется, он сначала удаляется. |
| [DeleteMedium](../../aspose.svg.dom.css/imedialist/deletemedium/)(*string*) | Удаляет из списка носитель, указанный как oldMedium. |

### См. также

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
