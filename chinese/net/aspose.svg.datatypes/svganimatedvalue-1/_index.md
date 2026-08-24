---
title: "SVGAnimatedValueT 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.DataTypes.SVGAnimatedValue1T 类。用于可以动画化的属性类型。"
type: docs
weight: 2200
url: /zh/net/aspose.svg.datatypes/svganimatedvalue-1/
---
## SVGAnimatedValue<T> class

用于可动画化类型的属性。

```csharp
public abstract class SVGAnimatedValue<T> : SVGValueType
```

| 参数 | 描述 |
| --- | --- |
| T | SVG 值对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [AnimVal](../../aspose.svg.datatypes/svganimatedvalue-1/animval/) { get; } | 如果给定的属性或属性正在进行动画，则包含该属性或属性的当前动画值。如果给定的属性或属性当前未进行动画，则包含与 baseVal 相同的值。 |
| [BaseVal](../../aspose.svg.datatypes/svganimatedvalue-1/baseval/) { get; set; } | 在应用任何动画之前，给定属性的基础值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |

### 另请参阅

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
