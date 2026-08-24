---
title: "SVGBuilderExtensions.AddFeDropShadow"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddFeDropShadow 方法。向构建器添加 feDropShadow 元素配置。此元素创建投影效果"
type: docs
weight: 200
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addfedropshadow/
---
## AddFeDropShadow<TBuilder>(*this TBuilder, Action&lt;SVGFEDropShadowElementBuilder&gt;*) {#addfedropshadow}

向构建器添加一个 'feDropShadow' 元素配置。该元素创建投影阴影效果。

```csharp
public static TBuilder AddFeDropShadow<TBuilder>(this TBuilder builder, 
    Action<SVGFEDropShadowElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 针对 'feDropShadow' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGFEDropShadowElementBuilder](../../svgfedropshadowelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDropShadow<TBuilder>(*this TBuilder, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDropShadowElementBuilder&gt;*) {#addfedropshadow_1}

向 SVG 构建器添加一个 'feDropShadow' 元素，为输入图形创建投影阴影效果。

```csharp
public static TBuilder AddFeDropShadow<TBuilder>(this TBuilder builder, double? dx = null, 
    double? dy = null, OneOf<double, (double, double)> stdDeviation = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDropShadowElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型，便于流式 API 使用。 |
| 构建器 | 将向其添加 'feDropShadow' 元素的 SVG 构建器实例。 |
| dx | 投影的水平偏移。可选参数。 |
| dy | 投影的垂直偏移。可选参数。 |
| stdDeviation | 投影中模糊操作的标准差。可以是 double 或两个 double 的 ValueTuple。可选参数。 |
| in | 将应用投影的输入图形。可以是字符串或 FilterInput。可选参数。 |
| result | 此过滤原语的结果标识符。可选参数。 |
| x | 过滤原语子区域的 x 坐标。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| y | 过滤原语子区域的 y 坐标。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| width | 过滤原语子区域的宽度。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| height | 过滤原语子区域的高度。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| fill | 元素的填充颜色、绘画或绘画服务器 ID。可选参数。 |
| stroke | 元素的描边颜色、绘画或绘画服务器 ID。可选参数。 |
| id | 过滤原语元素的唯一标识符。可选参数。 |
| 扩展 | 一个可选操作，用于进一步配置 SVGFEDropShadowElementBuilder。 |

### 返回值

构建器实例，允许方法链式调用。

### 另请参阅

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDropShadowElementBuilder](../../svgfedropshadowelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
