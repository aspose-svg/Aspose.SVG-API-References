---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGAngle ConvertToSpecifiedUnits. Сохраняет то же базовое сохранённое значение, но сбрасывает сохранённый идентификатор единицы на указанный unitType. Атрибуты объекта unitType, valueInSpecifiedUnits и valueAsString могут быть изменены в результате выполнения этого метода."
type: docs
weight: 50
url: /ru/net/aspose.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Сохранить то же базовое сохранённое значение, но сбросить сохранённый идентификатор единицы измерения на указанный unitType. Атрибуты объекта unitType, valueInSpecifiedUnits и valueAsString могут быть изменены в результате этого метода.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| unitType | UInt16 | Тип единицы, на который следует переключиться (например, SVG_ANGLETYPE_DEG). |

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) Выдается, если unitType имеет значение SVG_ANGLETYPE_UNKNOWN или не является допустимой константой типа единицы измерения (одной из остальных констант SVG_ANGLETYPE_*, определённых в этом интерфейсе). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Выдается, когда угол соответствует только для чтения атрибуту или когда сам объект только для чтения. |

### См. также

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
