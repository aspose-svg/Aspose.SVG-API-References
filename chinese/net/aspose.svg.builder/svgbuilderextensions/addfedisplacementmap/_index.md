---
title: "SVGBuilderExtensions.AddFeDisplacementMap"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddFeDisplacementMap 方法。向构建器添加 feDisplacementMap 元素的配置。此元素通过指定的矢量映射位移图像。"
type: docs
weight: 190
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addfedisplacementmap/
---
## AddFeDisplacementMap<TBuilder>(*this TBuilder, Action&lt;SVGFEDisplacementMapElementBuilder&gt;*) {#addfedisplacementmap}

向构建器添加一个 'feDisplacementMap' 元素配置。该元素通过指定的向量映射位移图像。

```csharp
public static TBuilder AddFeDisplacementMap<TBuilder>(this TBuilder builder, 
    Action<SVGFEDisplacementMapElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 用于 'feDisplacementMap' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGFEDisplacementMapElementBuilder](../../svgfedisplacementmapelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDisplacementMap<TBuilder>(*this TBuilder, double?, ChannelSelector?, ChannelSelector?, OneOf&lt;string, FilterInput&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDisplacementMapElementBuilder&gt;*) {#addfedisplacementmap_1}

向 SVG 构建器添加一个 'feDisplacementMap' 元素，创建基于第二来源颜色数据扭曲图像的效果。

```csharp
public static TBuilder AddFeDisplacementMap<TBuilder>(this TBuilder builder, double? scale = null, 
    ChannelSelector? xChannelSelector = default, ChannelSelector? yChannelSelector = default, 
    OneOf<string, FilterInput> @in = null, OneOf<string, FilterInput> in2 = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDisplacementMapElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型，便于流式 API 使用。 |
| 构建器 | 将向其添加 'feDisplacementMap' 元素的 SVG 构建器实例。 |
| scale | 决定位移量的比例因子。可选参数。 |
| xChannelSelector | 用于沿 x 轴位移的 in2 图像通道。可选参数。 |
| yChannelSelector | 用于沿 y 轴位移的 in2 图像通道。可选参数。 |
| in | 要位移的输入图像。可以是字符串或 FilterInput。可选参数。 |
| in2 | 提供位移数据的图像。可以是字符串或 FilterInput。可选参数。 |
| result | 此过滤原语的结果标识符。可选参数。 |
| x | 过滤原语子区域的 x 坐标。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| y | 过滤原语子区域的 y 坐标。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| width | 过滤原语子区域的宽度。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| height | 过滤原语子区域的高度。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| fill | 元素的填充颜色、绘画或绘画服务器 ID。可选参数。 |
| stroke | 元素的描边颜色、绘画或绘画服务器 ID。可选参数。 |
| id | 过滤原语元素的唯一标识符。可选参数。 |
| 扩展 | 用于进一步配置 SVGFEDisplacementMapElementBuilder 的可选操作。 |

### 返回值

构建器实例，允许方法链式调用。

### 另请参阅

* enum [ChannelSelector](../../channelselector/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDisplacementMapElementBuilder](../../svgfedisplacementmapelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
