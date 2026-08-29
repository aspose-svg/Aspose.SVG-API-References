---
title: "SVGLength.ValueAsString"
second_title: "Aspose.SVG для .NET справочник API"
description: "SVGLength ValueAsString property. Значение в виде строкового представления в единицах, указанных unitType. Установка этого атрибута приведёт к автоматическому обновлению value, valueInSpecifiedUnits и unitType, чтобы отразить эту настройку."
type: docs
weight: 30
url: /ru/net/aspose.svg.datatypes/svglength/valueasstring/
---
## SVGLength.ValueAsString property

Значение в виде строкового значения, в единицах, указанных в unitType. Установка этого атрибута автоматически обновит value, valueInSpecifiedUnits и unitType, чтобы отразить изменение.

```csharp
public string ValueAsString { get; set; }
```

### Property Value

Значение в виде строки.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`SYNTAX_ERR`](../../../aspose.svg.dom/domexception/syntax_err/) вызывается, если присвоенная строка не может быть разобрана как допустимая длина. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Возникает, когда длина соответствует атрибуту только для чтения или когда сам объект доступен только для чтения. |

### См. также

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
