---
title: "SVGAngle.ValueAsString"
second_title: "Aspose.SVG для .NET справочник API"
description: "Свойство SVGAngle ValueAsString. Значение угла как строка в единицах, указанных unitType. Установка этого атрибута приведёт к автоматическому обновлению value, valueInSpecifiedUnits и unitType, чтобы отразить эту настройку."
type: docs
weight: 30
url: /ru/net/aspose.svg.datatypes/svgangle/valueasstring/
---
## SVGAngle.ValueAsString property

Значение угла как строка, в единицах, указанных в unitType. Установка этого атрибута приведёт к автоматическому обновлению value, valueInSpecifiedUnits и unitType, чтобы отразить эту настройку.

```csharp
public string ValueAsString { get; set; }
```

### Property Value

Значение в виде строки.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`SYNTAX_ERR`](../../../aspose.svg.dom/domexception/syntax_err/) генерируется, если назначенная строка не может быть разобрана как допустимый угол. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Выдается, когда угол соответствует только для чтения атрибуту или когда сам объект только для чтения. |

### См. также

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
