---
title: "ITrueTypeFont интерфейс"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Drawing.ITrueTypeFont interface. Объявляет методы для работы с шрифтами TrueType."
type: docs
weight: 3540
url: /ru/net/aspose.svg.drawing/itruetypefont/
---
## ITrueTypeFont interface

Объявляет методы работы с шрифтами TrueType.

```csharp
public interface ITrueTypeFont
```

## Свойства

| Имя | Описание |
| --- | --- |
| [DataSize](../../aspose.svg.drawing/itruetypefont/datasize/) { get; } | Получает размер данных шрифта в байтах. |
| [FamilyName](../../aspose.svg.drawing/itruetypefont/familyname/) { get; } | Получает название семейства шрифта. |
| [FullFontName](../../aspose.svg.drawing/itruetypefont/fullfontname/) { get; } | Полное название шрифта обычно представляется как комбинация названий семейства и подсемейства. |
| [Style](../../aspose.svg.drawing/itruetypefont/style/) { get; } | Получает стиль шрифта, который объединяет значения правила font-face и данные из шрифта. |
| [SubFamilyName](../../aspose.svg.drawing/itruetypefont/subfamilyname/) { get; } | Подназвание Subfamily различает шрифт в группе с одинаковым названием семейства. Предполагается, что оно описывает стиль (italic, oblique) и толщину (light, bold, black и т.д.). Шрифт без особых различий по толщине или стилю должен иметь строку "Regular". |

## Методы

| Имя | Описание |
| --- | --- |
| [GetAscent](../../aspose.svg.drawing/itruetypefont/getascent/)(*float*) | Получает высоту восхождения шрифта в пунктах, используя указанный размер шрифта. |
| [GetData](../../aspose.svg.drawing/itruetypefont/getdata/)() | Открывает поток с данными шрифта. Вызывающий код отвечает за освобождение потока. |
| [GetDescent](../../aspose.svg.drawing/itruetypefont/getdescent/)(*float*) | Получает глубину спуска шрифта в пунктах, используя указанный размер шрифта. |

### См. также

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
