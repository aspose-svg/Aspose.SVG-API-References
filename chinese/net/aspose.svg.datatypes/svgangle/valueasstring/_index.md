---
title: "SVGAngle.ValueAsString"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGAngle ValueAsString 属性。以 unitType 表示的单位的字符串形式的角度值。设置此属性将导致 valueInSpecifiedUnits 和 unitType 自动更新以反映此设置"
type: docs
weight: 30
url: /zh/net/aspose.svg.datatypes/svgangle/valueasstring/
---
## SVGAngle.ValueAsString property

角度值为以 unitType 表示的单位的字符串。设置此属性将自动更新 value、valueInSpecifiedUnits 和 unitType 以反映此设置。

```csharp
public string ValueAsString { get; set; }
```

### Property Value

字符串形式的值。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`SYNTAX_ERR`](../../../aspose.svg.dom/domexception/syntax_err/) 在分配的字符串无法解析为有效角度时抛出。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) 在角度对应只读属性或对象本身为只读时抛出。 |

### 另请参阅

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
