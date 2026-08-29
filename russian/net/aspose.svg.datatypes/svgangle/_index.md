---
title: "Класс SVGAngle"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.DataTypes.SVGAngle. Интерфейс SVGAngle соответствует базовому типу данных angle"
type: docs
weight: 2070
url: /ru/net/aspose.svg.datatypes/svgangle/
---
## SVGAngle class

Интерфейс SVGAngle соответствует базовому типу данных angle.

```csharp
public class SVGAngle : SVGValueType
```

## Свойства

| Имя | Описание |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svgangle/unittype/) { get; } | Тип значения, указанный одним из констант SVG_ANGLETYPE_*, определённых в этом интерфейсе. |
| [Value](../../aspose.svg.datatypes/svgangle/value/) { get; set; } | Значение угла как число с плавающей запятой, в градусах. Установка этого атрибута приведёт к автоматическому обновлению valueInSpecifiedUnits и valueAsString, чтобы отразить эту настройку. |
| [ValueAsString](../../aspose.svg.datatypes/svgangle/valueasstring/) { get; set; } | Значение угла как строка, в единицах, указанных в unitType. Установка этого атрибута приведёт к автоматическому обновлению value, valueInSpecifiedUnits и unitType, чтобы отразить эту настройку. |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svgangle/valueinspecifiedunits/) { get; set; } | Значение угла как число с плавающей запятой, в единицах, указанных в unitType. Установка этого атрибута приведёт к автоматическому обновлению value и valueAsString, чтобы отразить эту настройку. |

## Методы

| Имя | Описание |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svgangle/converttospecifiedunits/)(*ushort*) | Сохранить то же базовое сохранённое значение, но сбросить сохранённый идентификатор единицы измерения на указанный unitType. Атрибуты объекта unitType, valueInSpecifiedUnits и valueAsString могут быть изменены в результате этого метода. |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и — при необходимости — управляемые ресурсы. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svgangle/newvaluespecifiedunits/)(*ushort, float*) | Сбросить значение как число с соответствующим unitType, тем самым заменив значения всех атрибутов объекта. |
| override [ToString](../../aspose.svg.datatypes/svgangle/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.svg.datatypes/svgangle/svg_angletype_deg/) | Тип единицы измерения был явно установлен в градусы. |
| const [SVG_ANGLETYPE_GRAD](../../aspose.svg.datatypes/svgangle/svg_angletype_grad/) | Тип единицы измерения — радианы. |
| const [SVG_ANGLETYPE_RAD](../../aspose.svg.datatypes/svgangle/svg_angletype_rad/) | Тип единицы измерения — радианы. |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.svg.datatypes/svgangle/svg_angletype_unknown/) | Тип единицы измерения не относится к предопределённым типам. Недопустимо пытаться определить новое значение этого типа или переключать существующее значение на этот тип. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.svg.datatypes/svgangle/svg_angletype_unspecified/) | Тип единицы измерения не указан (т.е. задано значение без единицы). Для углов значение без единицы рассматривается так же, как если бы были указаны градусы. |

### См. также

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
