---
title: "SVGBuilderExtensions.AddFeBlend"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddFeBlend 方法。向构建器添加 feBlend 元素配置。此元素定义两个图形之间的混合效果"
type: docs
weight: 130
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addfeblend/
---
## AddFeBlend<TBuilder>(*this TBuilder, Action&lt;SVGFEBlendElementBuilder&gt;*) {#addfeblend}

向构建器添加一个 'feBlend' 元素配置。此元素定义两个图形之间的混合效果。

```csharp
public static TBuilder AddFeBlend<TBuilder>(this TBuilder builder, 
    Action<SVGFEBlendElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 针对 'feBlend' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGFEBlendElementBuilder](../../svgfeblendelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeBlend<TBuilder>(*this TBuilder, BlendMode?, OneOf&lt;string, FilterInput&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEBlendElementBuilder&gt;*) {#addfeblend_1}

向 SVG 构建器添加一个 'feBlend' 元素，指定混合模式及过滤效果的其他各种属性。

```csharp
public static TBuilder AddFeBlend<TBuilder>(this TBuilder builder, BlendMode? mode = default, 
    OneOf<string, FilterInput> @in = null, OneOf<string, FilterInput> in2 = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEBlendElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型，便于流式 API 使用。 |
| 构建器 | 将向其添加 'feBlend' 元素的 SVG 构建器实例。 |
| 模式 | 要使用的混合模式。可选参数。 |
| in | 混合效果的第一个输入。可以是字符串或 FilterInput。可选参数。 |
| in2 | 混合效果的第二个输入。可以是字符串或 FilterInput。可选参数。 |
| result | 此过滤原语的结果标识符。可选参数。 |
| x | 过滤原语子区域的 x 坐标。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| y | 过滤原语子区域的 y 坐标。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| width | 过滤原语子区域的宽度。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| height | 过滤原语子区域的高度。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| fill | 元素的填充颜色、绘画或绘画服务器 ID。可选参数。 |
| stroke | 元素的描边颜色、绘画或绘画服务器 ID。可选参数。 |
| id | 过滤原语元素的唯一标识符。可选参数。 |
| 扩展 | 一个可选操作，用于进一步配置 SVGFEBlendElementBuilder。 |

### 返回值

构建器实例，允许方法链式调用。

### 另请参阅

* enum [BlendMode](../../blendmode/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEBlendElementBuilder](../../svgfeblendelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
