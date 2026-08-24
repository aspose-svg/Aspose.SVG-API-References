---
title: "SVGBuilderExtensions.AddUse"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddUse 方法。向构建器添加 use 元素配置。"
type: docs
weight: 550
url: /zh/net/aspose.svg.builder/svgbuilderextensions/adduse/
---
## AddUse<TBuilder>(*this TBuilder, Action&lt;SVGUseElementBuilder&gt;*) {#adduse}

向构建器添加一个 'use' 元素配置。

```csharp
public static TBuilder AddUse<TBuilder>(this TBuilder builder, 
    Action<SVGUseElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 用于 'use' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGUseElementBuilder](../../svguseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddUse<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGUseElementBuilder&gt;*) {#adduse_1}

向 SVG 构建器添加一个 'use' 元素，以便重用在 SVG 其他位置定义的现有元素。

```csharp
public static TBuilder AddUse<TBuilder>(this TBuilder builder, string href = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGUseElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型，便于流式 API 使用。 |
| 构建器 | 将向其添加 'use' 元素的 SVG 构建器实例。 |
| href | 要复用的现有元素的引用。可选参数。 |
| x | 复用元素放置位置的 x 坐标。可以是 double 或带有 LengthType 的 ValueTuple。可选参数。 |
| y | 复用元素放置位置的 y 坐标。可以是 double 或带有 LengthType 的 ValueTuple。可选参数。 |
| width | 复用元素的宽度。可以是 double 或带有 LengthType 的 ValueTuple。可选参数。 |
| height | 复用元素的高度。可以是 double 或带有 LengthType 的 ValueTuple。可选参数。 |
| fill | 元素的填充颜色、绘画或绘画服务器 ID。可选参数。 |
| stroke | 元素的描边颜色、绘画或绘画服务器 ID。可选参数。 |
| id | 元素的唯一标识符。可选参数。 |
| 扩展 | 一个可选操作，用于进一步配置 SVGUseElementBuilder。 |

### 返回值

构建器实例，允许方法链式调用。

### 另请参阅

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGUseElementBuilder](../../svguseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
