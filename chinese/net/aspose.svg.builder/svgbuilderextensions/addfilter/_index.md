---
title: "SVGBuilderExtensions.AddFilter"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddFilter 方法。向构建器添加过滤器元素配置"
type: docs
weight: 300
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addfilter/
---
## AddFilter<TBuilder>(*this TBuilder, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter}

向构建器添加一个 'filter' 元素配置。

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    Action<SVGFilterElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 用于 'filter' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFilter<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter_1}

向 SVG 构建器添加一个 'filter' 元素，定义可应用于 SVG 元素的滤镜效果。

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    CoordinateUnits? filterUnits = default, CoordinateUnits? primitiveUnits = default, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFilterElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型，便于流式 API 使用。 |
| 构建器 | 将向其添加 'filter' 元素的 SVG 构建器实例。 |
| filterUnits | 指定过滤器的 x、y、宽度和高度属性的坐标系。可选参数。 |
| primitiveUnits | 指定过滤器子元素属性的坐标系。可选参数。 |
| x | 过滤器区域的 x 坐标。可以是 double 或带有 LengthType 的 ValueTuple。可选参数。 |
| y | 过滤器区域的 y 坐标。可以是 double 或带有 LengthType 的 ValueTuple。可选参数。 |
| width | 过滤器区域的宽度。可以是 double 或带有 LengthType 的 ValueTuple。可选参数。 |
| height | 过滤器区域的高度。可以是 double 或带有 LengthType 的 ValueTuple。可选参数。 |
| fill | 过滤器元素的填充颜色或绘制。可选参数。 |
| stroke | 过滤器元素的描边颜色或绘制。可选参数。 |
| id | 过滤器元素的唯一标识符。可选参数。 |
| 扩展 | 用于进一步配置 SVGFilterElementBuilder 的可选操作。 |

### 返回值

构建器实例，允许方法链式调用。

### 另请参阅

* enum [CoordinateUnits](../../coordinateunits/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
