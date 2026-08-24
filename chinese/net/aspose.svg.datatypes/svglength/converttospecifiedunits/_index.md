---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGLength ConvertToSpecifiedUnits 方法。保持相同的底层存储值，但将存储的单位标识符重置为给定的 unitType。对象属性 unitType、valueInSpecifiedUnits 和 valueAsString 可能会因此方法而被修改。例如，如果原始值为 0.5cm，调用该方法将其转换为毫米，则 unitType 将更改为 SVG_LENGTHTYPE_MM，valueInSpecifiedUnits 将更改为数值 5，valueAsString 将更改为 5mm。"
type: docs
weight: 50
url: /zh/net/aspose.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

保持相同的底层存储值，但将存储的单位标识符重置为给定的 unitType。对象属性 unitType、valueInSpecifiedUnits 和 valueAsString 可能会因该方法而被修改。例如，如果原始值为 "0.5cm"，且调用该方法将其转换为毫米，则 unitType 将更改为 SVG_LENGTHTYPE_MM，valueInSpecifiedUnits 将更改为数值 5，valueAsString 将更改为 "5mm"。

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| unitType | UInt16 | 要切换到的单位类型（例如，SVG_LENGTHTYPE_MM）。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) 在 unitType 为 SVG_LENGTHTYPE_UNKNOWN 或不是有效的单位类型常量（此接口上定义的其他 SVG_LENGTHTYPE_* 常量之一）时抛出。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) 在长度对应只读属性或对象本身为只读时抛出。 |

### 另请参阅

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
