---
title: "SVGLength.ValueAsString"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGLength ValueAsString 属性。该值以 unitType 表示的单位的字符串形式呈现。设置此属性将自动更新 value、valueInSpecifiedUnits 和 unitType，以反映此设置。"
type: docs
weight: 30
url: /zh/net/aspose.svg.datatypes/svglength/valueasstring/
---
## SVGLength.ValueAsString property

该值为字符串，单位由 unitType 表示。设置此属性将自动更新 value、valueInSpecifiedUnits 和 unitType 以反映此设置。

```csharp
public string ValueAsString { get; set; }
```

### Property Value

字符串形式的值。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`SYNTAX_ERR`](../../../aspose.svg.dom/domexception/syntax_err/) 当分配的字符串无法解析为有效长度时抛出。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) 在长度对应只读属性或对象本身为只读时抛出。 |

### 另请参阅

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
