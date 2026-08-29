---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод NewValueSpecifiedUnits класса SVGLength. Сбрасывает значение как число с соответствующим unitType, заменяя тем самым значения всех атрибутов объекта"
type: docs
weight: 60
url: /ru/net/aspose.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Сбросить значение как число с соответствующим unitType, тем самым заменив значения всех атрибутов объекта.

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| unitType | UInt16 | Тип единицы измерения для значения. |
| valueInSpecifiedUnits | Single | Новое значение.. |

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) вызывается, если unitType имеет значение SVG_LENGTHTYPE_UNKNOWN или не является допустимой константой типа единицы (одной из остальных констант SVG_LENGTHTYPE_* , определённых в этом интерфейсе). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Возникает, когда длина соответствует атрибуту только для чтения или когда сам объект доступен только для чтения. |

### См. также

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
