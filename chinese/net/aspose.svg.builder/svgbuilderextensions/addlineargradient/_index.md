---
title: "SVGBuilderExtensions.AddLinearGradient"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddLinearGradient 方法。向构建器添加 linearGradient 元素配置"
type: docs
weight: 360
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addlineargradient/
---
## AddLinearGradient<TBuilder>(*this TBuilder, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient_1}

向构建器添加一个 'linearGradient' 元素配置。

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    Action<SVGLinearGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 用于 'linearGradient' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLinearGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient}

向 SVG 构建器添加一个 'linearGradient' 元素，指定其起始和结束位置以及其他渐变属性。

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1, OneOf<double, (double, LengthType)> y1, 
    OneOf<double, (double, LengthType)> x2, OneOf<double, (double, LengthType)> y2, 
    CoordinateUnits? gradientUnits, SpreadMethod? spreadMethod, string href = null, 
    string id = null, Action<SVGLinearGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型，便于流式 API 使用。 |
| 构建器 | 将向其添加 'linearGradient' 元素的 SVG 构建器实例。 |
| x1 | 渐变的起始 x 坐标。可以是 double 或带有 LengthType 的 ValueTuple。 |
| y1 | 渐变的起始 y 坐标。可以是 double 或带有 LengthType 的 ValueTuple。 |
| x2 | 渐变的结束 x 坐标。可以是 double 或带有 LengthType 的 ValueTuple。 |
| y2 | 渐变的结束 y 坐标。可以是 double 或带有 LengthType 的 ValueTuple。 |
| gradientUnits | 指定渐变的坐标系统。可选参数。 |
| spreadMethod | 定义渐变在起始点和结束点之外的扩展方式。可选参数。 |
| href | 对另一个渐变的引用（如果适用）。可选参数。 |
| id | 渐变元素的唯一标识符。可选参数。 |
| 扩展 | 用于进一步配置线性渐变元素构建器的可选操作。 |

### 返回值

构建器实例，允许方法链式调用。

### 另请参阅

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
