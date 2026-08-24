---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGAngle ConvertToSpecifiedUnits 方法。保持相同的底层存储值，但将存储的单位标识符重置为给定的 unitType。对象属性 unitType、valueInSpecifiedUnits 和 valueAsString 可能会因该方法而被修改。"
type: docs
weight: 50
url: /zh/net/aspose.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

保持相同的底层存储值，但将存储的单位标识符重置为给定的 unitType。对象属性 unitType、valueInSpecifiedUnits 和 valueAsString 可能会因该方法而被修改。

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| unitType | UInt16 | 要切换到的单位类型（例如，SVG_ANGLETYPE_DEG）。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) 在 unitType 为 SVG_ANGLETYPE_UNKNOWN 或不是有效的单位类型常量（此接口上定义的其他 SVG_ANGLETYPE_* 常量之一）时抛出。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) 在角度对应只读属性或对象本身为只读时抛出。 |

### 另请参阅

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
