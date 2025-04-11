---
title: SVGLength.NewValueSpecifiedUnits
second_title: Aspose.SVG for .NET API Reference
description: SVGLength NewValueSpecifiedUnits method. Reset the value as a number with an associated unitType thereby replacing the values for all of the attributes on the object
type: docs
weight: 60
url: /net/aspose.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Reset the value as a number with an associated unitType, thereby replacing the values for all of the attributes on the object.

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parameter | Type | Description |
| --- | --- | --- |
| unitType | UInt16 | The unit type for the value. |
| valueInSpecifiedUnits | Single | The new value.. |

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) Raised if unitType is SVG_LENGTHTYPE_UNKNOWN or not a valid unit type constant (one of the other SVG_LENGTHTYPE_* constants defined on this interface). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Raised when the length corresponds to a read only attribute or when the object itself is read only. |

### See Also

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
