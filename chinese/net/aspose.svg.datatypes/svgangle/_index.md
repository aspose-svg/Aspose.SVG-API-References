---
title: "SVGAngle 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.DataTypes.SVGAngle 类。SVGAngle 接口对应角度基本数据类型"
type: docs
weight: 2070
url: /zh/net/aspose.svg.datatypes/svgangle/
---
## SVGAngle class

SVGAngle 接口对应角度基本数据类型。

```csharp
public class SVGAngle : SVGValueType
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svgangle/unittype/) { get; } | 该值的类型由此接口上定义的 SVG_ANGLETYPE_* 常量之一指定。 |
| [Value](../../aspose.svg.datatypes/svgangle/value/) { get; set; } | 角度值为以度为单位的浮点数。设置此属性将自动更新 valueInSpecifiedUnits 和 valueAsString 以反映此设置。 |
| [ValueAsString](../../aspose.svg.datatypes/svgangle/valueasstring/) { get; set; } | 角度值为以 unitType 表示的单位的字符串。设置此属性将自动更新 value、valueInSpecifiedUnits 和 unitType 以反映此设置。 |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svgangle/valueinspecifiedunits/) { get; set; } | 角度值为以 unitType 表示的单位的浮点数。设置此属性将自动更新 value 和 valueAsString 以反映此设置。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svgangle/converttospecifiedunits/)(*ushort*) | 保持相同的底层存储值，但将存储的单位标识符重置为给定的 unitType。对象属性 unitType、valueInSpecifiedUnits 和 valueAsString 可能会因该方法而被修改。 |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svgangle/newvaluespecifiedunits/)(*ushort, float*) | 将值重置为带有关联 unitType 的数字，从而替换对象上所有属性的值。 |
| override [ToString](../../aspose.svg.datatypes/svgangle/tostring/)() | 返回表示此实例的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.svg.datatypes/svgangle/svg_angletype_deg/) | 单位类型已明确设置为度。 |
| const [SVG_ANGLETYPE_GRAD](../../aspose.svg.datatypes/svgangle/svg_angletype_grad/) | 单位类型为弧度。 |
| const [SVG_ANGLETYPE_RAD](../../aspose.svg.datatypes/svgangle/svg_angletype_rad/) | 单位类型为弧度。 |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.svg.datatypes/svgangle/svg_angletype_unknown/) | 单位类型不是预定义的单位类型之一。尝试定义此类型的新值或尝试将现有值切换到此类型都是无效的。 |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.svg.datatypes/svgangle/svg_angletype_unspecified/) | 未提供单位类型（即指定了无单位值）。对于角度，无单位值被视为等同于指定了度。 |

### 另请参阅

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
