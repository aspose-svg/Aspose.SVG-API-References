---
title: SVGAngle.ValueAsString
second_title: Aspose.SVG for .NET API Reference
description: SVGAngle ValueAsString property. The angle value as a string value in the units expressed by unitType. Setting this attribute will cause value valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting
type: docs
weight: 30
url: /net/aspose.svg.datatypes/svgangle/valueasstring/
---
## SVGAngle.ValueAsString property

The angle value as a string value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting.

```csharp
public string ValueAsString { get; set; }
```

### Property Value

The value as string.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`SYNTAX_ERR`](../../../aspose.svg.dom/domexception/syntax_err/) Raised if the assigned string cannot be parsed as a valid angle. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Raised when the angle corresponds to a read only attribute or when the object itself is read only. |

### See Also

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
