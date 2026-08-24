---
title: "SVGBuilderExtensions.Points"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions Points 方法。使用 double 数组设置 SVG 元素的 points 属性"
type: docs
weight: 1910
url: /zh/net/aspose.svg.builder/svgbuilderextensions/points/
---
## Points<TBuilder>(*this TBuilder, params double[]*) {#points}

使用双精度数组设置 SVG 元素的 'points' 属性。

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params double[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| points | 表示点的 double 数组（必须为偶数）。 |

### 返回值

用于链式调用的构建器实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果提供的点数为奇数，则抛出异常。 |

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Points<TBuilder>(*this TBuilder, params PointF[]*) {#points_1}

使用 PointF 对象数组设置 SVG 元素的 'points' 属性。

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params PointF[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| points | 表示点的 PointF 对象数组。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
