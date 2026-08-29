---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGAngle NewValueSpecifiedUnits. Сбрасывает значение как число с соответствующим unitType, тем самым заменяя значения всех атрибутов объекта."
type: docs
weight: 60
url: /ru/net/aspose.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Сбросить значение как число с соответствующим unitType, тем самым заменив значения всех атрибутов объекта.

```csharp
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newUnitType | UInt16 | Тип единицы измерения для значения (например, SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | Значение угла. |

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) Выдается, если unitType имеет значение SVG_ANGLETYPE_UNKNOWN или не является допустимой константой типа единицы измерения (одной из остальных констант SVG_ANGLETYPE_*, определённых в этом интерфейсе). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Выдается, когда угол соответствует только для чтения атрибуту или когда сам объект только для чтения. |

### См. также

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
