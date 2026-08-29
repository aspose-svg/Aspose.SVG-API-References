---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGLength ConvertToSpecifiedUnits. Сохраняет то же базовое сохранённое значение, но сбрасывает сохранённый идентификатор единицы на указанный unitType. Атрибуты объекта unitType, valueInSpecifiedUnits и valueAsString могут быть изменены в результате вызова этого метода. Например, если исходное значение было 0,5 см и метод был вызван для преобразования в миллиметры, то unitType будет изменён на SVG_LENGTHTYPE_MM, valueInSpecifiedUnits будет изменено на числовое значение 5, а valueAsString будет изменено на 5mm."
type: docs
weight: 50
url: /ru/net/aspose.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Сохраняет то же базовое сохранённое значение, но сбрасывает сохранённый идентификатор единицы измерения на указанный unitType. Атрибуты объекта unitType, valueInSpecifiedUnits и valueAsString могут быть изменены в результате вызова этого метода. Например, если исходное значение было \"0.5cm\" и метод был вызван для преобразования в миллиметры, то unitType будет изменён на SVG_LENGTHTYPE_MM, valueInSpecifiedUnits будет изменено на числовое значение 5, а valueAsString будет изменено на \"5mm\".

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| unitType | UInt16 | Тип единицы, на который следует переключиться (например, SVG_LENGTHTYPE_MM). |

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) вызывается, если unitType имеет значение SVG_LENGTHTYPE_UNKNOWN или не является допустимой константой типа единицы (одной из остальных констант SVG_LENGTHTYPE_* , определённых в этом интерфейсе). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Возникает, когда длина соответствует атрибуту только для чтения или когда сам объект доступен только для чтения. |

### См. также

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
