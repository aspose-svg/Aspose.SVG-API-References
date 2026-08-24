---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGLength NewValueSpecifiedUnits 方法。将值重置为带有关联 unitType 的数字，从而替换对象上所有属性的值。"
type: docs
weight: 60
url: /zh/net/aspose.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

将值重置为带有关联 unitType 的数字，从而替换对象上所有属性的值。

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| unitType | UInt16 | 该值的单位类型。 |
| valueInSpecifiedUnits | Single | 新的值.. |

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) 在 unitType 为 SVG_LENGTHTYPE_UNKNOWN 或不是有效的单位类型常量（此接口上定义的其他 SVG_LENGTHTYPE_* 常量之一）时抛出。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) 在长度对应只读属性或对象本身为只读时抛出。 |

### 另请参阅

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
