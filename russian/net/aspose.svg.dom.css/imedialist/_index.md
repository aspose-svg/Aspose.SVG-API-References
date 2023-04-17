---
title: Interface IMediaList
second_title: Справочник по Aspose.SVG для .NET API
description: Aspose.Svg.Dom.Css.IMediaList интерфейс. Интерфейс MediaList обеспечивает абстракцию упорядоченной коллекции медиа не определяя и не ограничивая реализацию этой коллекции. Пустой список аналогичен списку который содержит носитель все.
type: docs
weight: 730
url: /ru/net/aspose.svg.dom.css/imedialist/
---
## IMediaList interface

Интерфейс MediaList обеспечивает абстракцию упорядоченной коллекции медиа, не определяя и не ограничивая реализацию этой коллекции. Пустой список аналогичен списку, который содержит носитель «все».

```csharp
public interface IMediaList : IEnumerable<string>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Item](../../aspose.svg.dom.css/imedialist/item/) { get; } | Возвращает индекс в списке. Если индекс больше или равен количеству носителей в списке, возвращается null. Индекс СМИ. |
| [Length](../../aspose.svg.dom.css/imedialist/length/) { get; } | Количество носителей в списке. Диапазон допустимых носителей: от 0 до длины 1 включительно. |
| [MediaText](../../aspose.svg.dom.css/imedialist/mediatext/) { get; } | Анализируемое текстовое представление списка мультимедиа. Это список медиафайлов, разделенных запятыми. |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendMedium](../../aspose.svg.dom.css/imedialist/appendmedium/)(string) | Добавляет носитель newMedium в конец списка. Если новое средство уже используется, оно сначала удаляется. |
| [DeleteMedium](../../aspose.svg.dom.css/imedialist/deletemedium/)(string) | Удаляет из списка носитель, указанный oldMedium. |

### Смотрите также

* пространство имен [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* сборка [Aspose.SVG](../../)


