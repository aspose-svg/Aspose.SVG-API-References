---
title: "Класс SVGLength"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.DataTypes.SVGLength. Интерфейс SVGLength соответствует базовому типу данных длина. Объект SVGLength может быть помечен как только для чтения, что означает, что попытки изменить объект приведут к выбросу исключения, как описано ниже."
type: docs
weight: 2210
url: /ru/net/aspose.svg.datatypes/svglength/
---
## SVGLength class

Интерфейс SVGLength соответствует базовому типу данных length. Объект SVGLength может быть помечен как только для чтения, что означает, что попытки изменить объект приведут к выбросу исключения, как описано ниже.

```csharp
public class SVGLength : SVGValueType
```

## Свойства

| Имя | Описание |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svglength/unittype/) { get; } | Тип значения, указанный одним из констант SVG_LENGTHTYPE_*, определённых в этом интерфейсе. |
| [Value](../../aspose.svg.datatypes/svglength/value/) { get; set; } | Значение в виде числа с плавающей точкой, в пользовательских единицах. Установка этого атрибута автоматически обновит valueInSpecifiedUnits и valueAsString, чтобы отразить изменение. |
| [ValueAsString](../../aspose.svg.datatypes/svglength/valueasstring/) { get; set; } | Значение в виде строкового значения, в единицах, указанных в unitType. Установка этого атрибута автоматически обновит value, valueInSpecifiedUnits и unitType, чтобы отразить изменение. |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svglength/valueinspecifiedunits/) { get; set; } | Значение в виде числа с плавающей точкой, в единицах, указанных в unitType. Установка этого атрибута автоматически обновит value и valueAsString, чтобы отразить изменение. |

## Методы

| Имя | Описание |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svglength/converttospecifiedunits/)(*ushort*) | Сохраняет то же базовое сохранённое значение, но сбрасывает сохранённый идентификатор единицы измерения на указанный unitType. Атрибуты объекта unitType, valueInSpecifiedUnits и valueAsString могут быть изменены в результате вызова этого метода. Например, если исходное значение было \"0.5cm\" и метод был вызван для преобразования в миллиметры, то unitType будет изменён на SVG_LENGTHTYPE_MM, valueInSpecifiedUnits будет изменено на числовое значение 5, а valueAsString будет изменено на \"5mm\". |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и — при необходимости — управляемые ресурсы. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svglength/newvaluespecifiedunits/)(*ushort, float*) | Сбросить значение как число с соответствующим unitType, тем самым заменив значения всех атрибутов объекта. |
| override [ToString](../../aspose.svg.datatypes/svglength/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.svg.datatypes/svglength/svg_lengthtype_cm/) | Значение было указано с использованием единиц cm, определённых в CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../aspose.svg.datatypes/svglength/svg_lengthtype_ems/) | Значение было указано с использованием единиц em, определённых в CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../aspose.svg.datatypes/svglength/svg_lengthtype_exs/) | Значение было указано с использованием единиц ex, определённых в CSS2. |
| const [SVG_LENGTHTYPE_IN](../../aspose.svg.datatypes/svglength/svg_lengthtype_in/) | Значение было указано с использованием единиц in, определённых в CSS2. |
| const [SVG_LENGTHTYPE_MM](../../aspose.svg.datatypes/svglength/svg_lengthtype_mm/) | Значение было указано с использованием единиц mm, определённых в CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.svg.datatypes/svglength/svg_lengthtype_number/) | Тип единицы не был указан (т.е. было указано безединичное значение), что означает значение в пользовательских единицах. |
| const [SVG_LENGTHTYPE_PC](../../aspose.svg.datatypes/svglength/svg_lengthtype_pc/) | Значение было указано с использованием единиц pc, определённых в CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.svg.datatypes/svglength/svg_lengthtype_percentage/) | Было указано процентное значение. |
| const [SVG_LENGTHTYPE_PT](../../aspose.svg.datatypes/svglength/svg_lengthtype_pt/) | Значение было указано с использованием единиц pt, определённых в CSS2. |
| const [SVG_LENGTHTYPE_PX](../../aspose.svg.datatypes/svglength/svg_lengthtype_px/) | Значение было указано с использованием единиц px, определённых в CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.svg.datatypes/svglength/svg_lengthtype_unknown/) | Тип единицы измерения не относится к предопределённым типам. Недопустимо пытаться определить новое значение этого типа или переключать существующее значение на этот тип. |

### См. также

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
