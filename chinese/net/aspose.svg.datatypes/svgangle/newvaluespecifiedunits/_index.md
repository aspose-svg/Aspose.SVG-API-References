---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGAngle NewValueSpecifiedUnits 方法。将值重置为带有关联 unitType 的数字，从而替换对象上所有属性的值"
type: docs
weight: 60
url: /zh/net/aspose.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

将值重置为带有关联 unitType 的数字，从而替换对象上所有属性的值。

```csharp
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newUnitType | UInt16 | 值的单位类型（例如，SVG_ANGLETYPE_DEG）。 |
| valueInSpecifiedUnits | Single | 角度值。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) 在 unitType 为 SVG_ANGLETYPE_UNKNOWN 或不是有效的单位类型常量（此接口上定义的其他 SVG_ANGLETYPE_* 常量之一）时抛出。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) 在角度对应只读属性或对象本身为只读时抛出。 |

### 另请参阅

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
