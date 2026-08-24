---
title: "SVGGeometryElement.Combine"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGGeometryElement Combine 方法。将此几何体与另一个 SVG 几何体使用布尔运算合并，并返回一个包含结果的新路径元素"
type: docs
weight: 20
url: /zh/net/aspose.svg/svggeometryelement/combine/
---
## SVGGeometryElement.Combine method

使用布尔运算将此几何体与另一个 SVG 几何体组合，并返回包含结果的新 `<path>` 元素。

```csharp
public SVGPathElement Combine(SVGGeometryElement geometryElement, BooleanPathOp op)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| geometryElement | SVGGeometryElement | 要合并的另一个几何体。必须位于同一文档中。 |
| op | BooleanPathOp | 要应用的布尔运算符：并集 (Union) (A UNION B)、差集 (Difference) (A - B)、交集 (Intersection) (A INTERSECT B) 或排除 (Exclusion) (XOR)。 |

### 返回值

一个新的 [`SVGPathElement`](../../svgpathelement/) ，其 `d` 属性在根 `<svg>` 用户空间（CSS 像素）中编码结果。该元素未被添加到 DOM 中。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 如果 *geometryElement* 为 null，则抛出此异常。 |
| InvalidOperationException | 如果此元素没有所属文档，则抛出此异常。 |
| NotSupportedException | 当布尔路径操作不可用时抛出；此功能需要 SkiaSharp 后端（安装 Aspose.SVG.Drawing.SkiaSharp 包）。 |

### 另请参阅

* class [SVGPathElement](../../svgpathelement/)
* enum [BooleanPathOp](../../../aspose.svg.rendering/booleanpathop/)
* class [SVGGeometryElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
