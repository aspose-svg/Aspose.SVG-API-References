---
title: "SVGBuilderExtensions.AddFeFlood"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddFeFlood 方法。向构建器添加 feFlood 元素配置。此元素使用指定颜色填充过滤器子区域。"
type: docs
weight: 210
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addfeflood/
---
## AddFeFlood<TBuilder>(*this TBuilder, Action&lt;SVGFEFloodElementBuilder&gt;*) {#addfeflood}

向构建器添加一个 'feFlood' 元素配置。该元素用指定颜色填充滤镜子区域。

```csharp
public static TBuilder AddFeFlood<TBuilder>(this TBuilder builder, 
    Action<SVGFEFloodElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 针对 'feFlood' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGFEFloodElementBuilder](../../svgfefloodelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeFlood<TBuilder>(*this TBuilder, Color?, double?, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEFloodElementBuilder&gt;*) {#addfeflood_1}

向 SVG 构建器添加一个 'feFlood' 元素，在整个滤镜子区域创建统一的填充颜色效果。

```csharp
public static TBuilder AddFeFlood<TBuilder>(this TBuilder builder, Color? floodColor = default, 
    double? floodOpacity = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEFloodElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型，便于流式 API 使用。 |
| 构建器 | 将添加 'feFlood' 元素的 SVG 构建器实例。 |
| floodColor | 用于泛洪效果的颜色。可选参数。 |
| floodOpacity | 泛洪颜色的不透明度级别。可选参数。 |
| result | 此过滤原语的结果标识符。可选参数。 |
| x | 过滤原语子区域的 x 坐标。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| y | 过滤原语子区域的 y 坐标。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| width | 过滤原语子区域的宽度。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| height | 过滤原语子区域的高度。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| fill | 元素的填充颜色、绘画或绘画服务器 ID。可选参数。 |
| stroke | 元素的描边颜色、绘画或绘画服务器 ID。可选参数。 |
| id | 过滤原语元素的唯一标识符。可选参数。 |
| 扩展 | 一个可选操作，用于进一步配置 SVGFEFloodElementBuilder。 |

### 返回值

构建器实例，允许方法链式调用。

### 另请参阅

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEFloodElementBuilder](../../svgfefloodelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
