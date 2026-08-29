---
title: "Класс SVGException"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.SVGException. Это исключение возникает, когда конкретную операцию SVG выполнить невозможно"
type: docs
weight: 5300
url: /ru/net/aspose.svg/svgexception/
---
## SVGException class

Это исключение возникает, когда конкретную операцию SVG выполнить невозможно.

```csharp
public class SVGException : PlatformException
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SVGException](svgexception/)(*ushort*) | Инициализирует новый экземпляр класса `SVGException`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Code](../../aspose.svg/svgexception/code/) { get; } | Код, идентифицирующий причину, по которой запрошенную операцию нельзя выполнить. Значение этого члена будет одной из констант в группе кодов SVGException. |
| virtual [Data](../../system/exception/data/) { get; } |  |
| virtual [HelpLink](../../system/exception/helplink/) { get; set; } |  |
| [HResult](../../system/exception/hresult/) { get; set; } |  |
| [InnerException](../../system/exception/innerexception/) { get; } |  |
| virtual [Message](../../system/exception/message/) { get; } |  |
| virtual [Source](../../system/exception/source/) { get; set; } |  |
| virtual [StackTrace](../../system/exception/stacktrace/) { get; } |  |
| [TargetSite](../../system/exception/targetsite/) { get; } |  |

## Поля

| Имя | Описание |
| --- | --- |
| const [SVG_INVALID_VALUE_ERR](../../aspose.svg/svgexception/svg_invalid_value_err/) | Выбрасывается, когда в операцию передано недопустимое значение или оно назначено атрибуту. |
| const [SVG_MATRIX_NOT_INVERTABLE](../../aspose.svg/svgexception/svg_matrix_not_invertable/) | Выбрасывается, когда предпринимается попытка обратить матрицу, которая не обратима. |
| const [SVG_WRONG_TYPE_ERR](../../aspose.svg/svgexception/svg_wrong_type_err/) | Выбрасывается, когда в операцию передан объект неверного типа. |

### См. также

* class [PlatformException](../platformexception/)
* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
