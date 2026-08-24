---
title: "SVGBuilderExtensions.AddFeColorMatrix"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddFeColorMatrix 方法。向构建器添加 feColorMatrix 元素配置。此元素对每个像素的颜色和 alpha 值应用矩阵变换"
type: docs
weight: 140
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addfecolormatrix/
---
## AddFeColorMatrix<TBuilder>(*this TBuilder, Action&lt;SVGFEColorMatrixElementBuilder&gt;*) {#addfecolormatrix_1}

向构建器添加一个 'feColorMatrix' 元素配置。此元素对每个像素的颜色和 alpha 值应用矩阵变换。

```csharp
public static TBuilder AddFeColorMatrix<TBuilder>(this TBuilder builder, 
    Action<SVGFEColorMatrixElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 用于 'feColorMatrix' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGFEColorMatrixElementBuilder](../../svgfecolormatrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeColorMatrix<TBuilder>(*this TBuilder, [ColorMatrixOperation](../../colormatrixoperation/), double[], OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEColorMatrixElementBuilder&gt;*) {#addfecolormatrix}

向 SVG 构建器添加一个 'feColorMatrix' 元素，指定颜色矩阵操作的类型及过滤效果的其他各种属性。

```csharp
public static TBuilder AddFeColorMatrix<TBuilder>(this TBuilder builder, ColorMatrixOperation type, 
    double[] values = null, OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEColorMatrixElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型，便于流式 API 使用。 |
| 构建器 | 将添加 'feColorMatrix' 元素的 SVG 构建器实例。 |
| type | 要应用的颜色矩阵操作类型。 |
| values | 颜色矩阵操作的值。可选参数。 |
| in | 颜色矩阵效果的输入。可以是字符串或 FilterInput。可选参数。 |
| result | 此过滤原语的结果标识符。可选参数。 |
| x | 过滤原语子区域的 x 坐标。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| y | 过滤原语子区域的 y 坐标。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| width | 过滤原语子区域的宽度。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| height | 过滤原语子区域的高度。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| fill | 元素的填充颜色、绘画或绘画服务器 ID。可选参数。 |
| stroke | 元素的描边颜色、绘画或绘画服务器 ID。可选参数。 |
| id | 过滤原语元素的唯一标识符。可选参数。 |
| 扩展 | 用于进一步配置 SVGFEColorMatrixElementBuilder 的可选操作。 |

### 返回值

构建器实例，允许方法链式调用。

### 另请参阅

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEColorMatrixElementBuilder](../../svgfecolormatrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
