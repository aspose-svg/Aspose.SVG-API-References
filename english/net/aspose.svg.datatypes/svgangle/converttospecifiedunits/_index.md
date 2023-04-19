---
title: SVGAngle.ConvertToSpecifiedUnits
second_title: Aspose.SVG for .NET API Reference
description: SVGAngle method. Preserve the same underlying stored value but reset the stored unit identifier to the given unitType. Object attributes unitType valueInSpecifiedUnits and valueAsString might be modified as a result of this method
type: docs
weight: 50
url: /net/aspose.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Preserve the same underlying stored value, but reset the stored unit identifier to the given unitType. Object attributes unitType, valueInSpecifiedUnits and valueAsString might be modified as a result of this method.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| unitType | UInt16 | The unit type to switch to (e.g., SVG_ANGLETYPE_DEG). |

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) Raised if unitType is SVG_ANGLETYPE_UNKNOWN or not a valid unit type constant (one of the other SVG_ANGLETYPE_* constants defined on this interface). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Raised when the angle corresponds to a read only attribute or when the object itself is read only. |

### See Also

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../svgangle/)
* assembly [Aspose.SVG](../../../)
