---
title: "SVGPoint 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.DataTypes.SVGPoint 类。许多 SVG DOM 接口引用 SVGPoint 类的对象。SVGPoint 是一个 x y 坐标对。当在矩阵运算中使用时，SVGPoint 被视为形式为 x y 1 的向量。如果 SVGRect 对象被指定为只读，则尝试为其属性赋值将导致抛出异常"
type: docs
weight: 2260
url: /zh/net/aspose.svg.datatypes/svgpoint/
---
## SVGPoint class

许多 SVG DOM 接口引用类 SVGPoint 的对象。SVGPoint 是一个 (x, y) 坐标对。在矩阵运算中，SVGPoint 被视为以下形式的向量： [x] [y] [1] 如果 SVGRect 对象被指定为只读，则尝试为其属性赋值将导致抛出异常。

```csharp
public class SVGPoint : SVGValueType
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [X](../../aspose.svg.datatypes/svgpoint/x/) { get; set; } | X 坐标。 |
| [Y](../../aspose.svg.datatypes/svgpoint/y/) { get; set; } | Y 坐标。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [MatrixTransform](../../aspose.svg.datatypes/svgpoint/matrixtransform/)(*[SVGMatrix](../svgmatrix/)*) | 对该 SVGPoint 对象应用 2x3 矩阵变换，并返回一个新的、已变换的 SVGPoint 对象：newpoint = matrix* thispoint |
| override [ToString](../../aspose.svg.datatypes/svgpoint/tostring/)() | 返回表示此实例的字符串。 |

### 另请参阅

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
