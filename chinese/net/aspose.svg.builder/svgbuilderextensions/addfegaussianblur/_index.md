---
title: "SVGBuilderExtensions.AddFeGaussianBlur"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddFeGaussianBlur 方法。向构建器添加 feGaussianBlur 元素配置。此元素对输入图像应用高斯模糊。"
type: docs
weight: 220
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addfegaussianblur/
---
## AddFeGaussianBlur<TBuilder>(*this TBuilder, Action&lt;SVGFEGaussianBlurElementBuilder&gt;*) {#addfegaussianblur_1}

向构建器添加一个 'feGaussianBlur' 元素配置。该元素对输入图像应用高斯模糊。

```csharp
public static TBuilder AddFeGaussianBlur<TBuilder>(this TBuilder builder, 
    Action<SVGFEGaussianBlurElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 针对 'feGaussianBlur' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGFEGaussianBlurElementBuilder](../../svgfegaussianblurelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeGaussianBlur<TBuilder>(*this TBuilder, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEGaussianBlurElementBuilder&gt;*) {#addfegaussianblur}

向 SVG 构建器添加一个 'feGaussianBlur' 元素，对输入图像应用高斯模糊效果。

```csharp
public static TBuilder AddFeGaussianBlur<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, double)> stdDeviation = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEGaussianBlurElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型，便于流式 API 使用。 |
| 构建器 | 将向其添加 'feGaussianBlur' 元素的 SVG 构建器实例。 |
| stdDeviation | 模糊操作的标准差。可以是 double 或包含两个 double 的 ValueTuple。可选参数。 |
| in | 将对其应用高斯模糊的输入图像。可以是字符串或 FilterInput。可选参数。 |
| result | 此过滤原语的结果标识符。可选参数。 |
| x | 过滤原语子区域的 x 坐标。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| y | 过滤原语子区域的 y 坐标。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| width | 过滤原语子区域的宽度。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| height | 过滤原语子区域的高度。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| fill | 元素的填充颜色、绘画或绘画服务器 ID。可选参数。 |
| stroke | 元素的描边颜色、绘画或绘画服务器 ID。可选参数。 |
| id | 过滤原语元素的唯一标识符。可选参数。 |
| 扩展 | 用于进一步配置 SVGFEGaussianBlurElementBuilder 的可选操作。 |

### 返回值

构建器实例，允许方法链式调用。

### 另请参阅

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEGaussianBlurElementBuilder](../../svgfegaussianblurelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
