---
title: "SVGBuilderExtensions.AddRadialGradient"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddRadialGradient 方法。向构建器添加 radialGradient 元素的配置。"
type: docs
weight: 440
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addradialgradient/
---
## AddRadialGradient<TBuilder>(*this TBuilder, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient_1}

向构建器添加一个 'radialGradient' 元素配置。

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    Action<SVGRadialGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 用于 'radialGradient' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRadialGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient}

向 SVG 构建器添加一个 'radialGradient' 元素，指定其中心、半径和焦点，以及其他渐变属性。

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<double, (double, LengthType)> fx = null, 
    OneOf<double, (double, LengthType)> fy = null, CoordinateUnits? gradientUnits = default, 
    SpreadMethod? spreadMethod = default, string href = null, string id = null, 
    Action<SVGRadialGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型，便于流式 API 使用。 |
| 构建器 | 将向其添加 'radialGradient' 元素的 SVG 构建器实例。 |
| cx | 渐变中心的 x 坐标。可以是 double 或带有 LengthType 的 ValueTuple。可选参数。 |
| cy | 渐变中心的 y 坐标。可以是 double 或带有 LengthType 的 ValueTuple。可选参数。 |
| r | 渐变的半径。可以是 double 或带有 LengthType 的 ValueTuple。可选参数。 |
| fx | 渐变焦点的 x 坐标。可以是 double 或带有 LengthType 的 ValueTuple。可选参数。 |
| fy | 渐变焦点的 y 坐标。可以是 double 或带有 LengthType 的 ValueTuple。可选参数。 |
| gradientUnits | 指定渐变的坐标系统。可选参数。 |
| spreadMethod | 定义渐变在起始点和结束点之外的扩展方式。可选参数。 |
| href | 对另一个渐变的引用（如果适用）。可选参数。 |
| id | 渐变元素的唯一标识符。可选参数。 |
| 扩展 | 用于进一步配置 radial gradient 元素构建器的可选操作。 |

### 返回值

构建器实例，允许方法链式调用。

### 另请参阅

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
