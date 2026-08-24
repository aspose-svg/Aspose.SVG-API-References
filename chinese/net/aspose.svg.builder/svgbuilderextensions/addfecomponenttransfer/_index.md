---
title: "SVGBuilderExtensions.AddFeComponentTransfer"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddFeComponentTransfer 方法。向构建器添加 feComponentTransfer 元素配置。此元素对颜色通道的数据进行逐组件重新映射。"
type: docs
weight: 150
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addfecomponenttransfer/
---
## AddFeComponentTransfer<TBuilder>(*this TBuilder, Action&lt;SVGFEComponentTransferElementBuilder&gt;*) {#addfecomponenttransfer}

向构建器添加一个 'feComponentTransfer' 元素配置。此元素对颜色通道的数据执行逐分量重新映射。

```csharp
public static TBuilder AddFeComponentTransfer<TBuilder>(this TBuilder builder, 
    Action<SVGFEComponentTransferElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 针对 'feComponentTransfer' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGFEComponentTransferElementBuilder](../../svgfecomponenttransferelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeComponentTransfer<TBuilder>(*this TBuilder, Action&lt;SVGFEFuncAElementBuilder&gt;, Action&lt;SVGFEFuncRElementBuilder&gt;, Action&lt;SVGFEFuncGElementBuilder&gt;, Action&lt;SVGFEFuncBElementBuilder&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEComponentTransferElementBuilder&gt;*) {#addfecomponenttransfer_1}

向 SVG 构建器添加一个 'feComponentTransfer' 元素，允许对颜色通道的数据进行逐分量重新映射。

```csharp
public static TBuilder AddFeComponentTransfer<TBuilder>(this TBuilder builder, 
    Action<SVGFEFuncAElementBuilder> a = null, Action<SVGFEFuncRElementBuilder> r = null, 
    Action<SVGFEFuncGElementBuilder> g = null, Action<SVGFEFuncBElementBuilder> b = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEComponentTransferElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型，便于流式 API 使用。 |
| 构建器 | 将添加 'feComponentTransfer' 元素的 SVG 构建器实例。 |
| a | 用于配置 alpha 通道的 'feFuncA' 组件的操作。可选参数。 |
| r | 用于配置红色通道的 'feFuncR' 组件的操作。可选参数。 |
| g | 用于配置绿色通道的 'feFuncG' 组件的操作。可选参数。 |
| b | 用于配置蓝色通道的 'feFuncB' 组件的操作。可选参数。 |
| in | 组件传输效果的输入。可以是字符串或 FilterInput。可选参数。 |
| result | 此过滤原语的结果标识符。可选参数。 |
| x | 过滤原语子区域的 x 坐标。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| y | 过滤原语子区域的 y 坐标。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| width | 过滤原语子区域的宽度。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| height | 过滤原语子区域的高度。可以是 double 或带 LengthType 的 ValueTuple。可选参数。 |
| fill | 元素的填充颜色、绘画或绘画服务器 ID。可选参数。 |
| stroke | 元素的描边颜色、绘画或绘画服务器 ID。可选参数。 |
| id | 过滤原语元素的唯一标识符。可选参数。 |
| 扩展 | 用于进一步配置 SVGFEComponentTransferElementBuilder 的可选操作。 |

### 返回值

构建器实例，允许方法链式调用。

### 另请参阅

* class [SVGFEFuncAElementBuilder](../../svgfefuncaelementbuilder/)
* class [SVGFEFuncRElementBuilder](../../svgfefuncrelementbuilder/)
* class [SVGFEFuncGElementBuilder](../../svgfefuncgelementbuilder/)
* class [SVGFEFuncBElementBuilder](../../svgfefuncbelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEComponentTransferElementBuilder](../../svgfecomponenttransferelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
