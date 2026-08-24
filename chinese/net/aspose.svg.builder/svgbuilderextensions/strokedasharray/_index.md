---
title: "SVGBuilderExtensions.StrokeDashArray"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions StrokeDashArray 方法。设置 SVG 元素的 stroke-dasharray 属性，定义用于绘制描边的虚线和间隙模式"
type: docs
weight: 2090
url: /zh/net/aspose.svg.builder/svgbuilderextensions/strokedasharray/
---
## StrokeDashArray<TBuilder>(*this TBuilder, params double[]*) {#strokedasharray_1}

为 SVG 元素设置 'stroke-dasharray' 属性，定义用于绘制描边的虚线和间隙模式。

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, params double[] dashArray)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| dashArray | 虚线长度的数组。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## StrokeDashArray<TBuilder>(*this TBuilder, [Dash](../../dash/)*) {#strokedasharray}

使用预定义的虚线模式为 SVG 元素设置 'stroke-dasharray' 属性。

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, Dash value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| value | 要设置的虚线模式。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [Dash](../../dash/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
