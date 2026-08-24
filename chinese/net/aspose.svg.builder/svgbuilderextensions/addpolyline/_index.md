---
title: "SVGBuilderExtensions.AddPolyline"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddPolyline 方法。向构建器添加 polyline 元素的配置。"
type: docs
weight: 430
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addpolyline/
---
## AddPolyline<TBuilder>(*this TBuilder, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline_1}

向构建器添加一个 'polyline' 元素配置。

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, 
    Action<SVGPolylineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 用于 'polyline' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolyline<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline}

向 SVG 构建器添加一个 'polyline' 元素，指定其顶点和样式。

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolylineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型，便于流式 API 使用。 |
| 构建器 | 将向其添加 'polyline' 元素的 SVG 构建器实例。 |
| points | 表示折线点的 double 数组（交替的 x 和 y 坐标）。 |
| fill | 折线的填充颜色或绘画样式。可以是 Color、Paint 枚举值或绘画服务器 ID。可选参数。 |
| stroke | 折线的描边颜色或绘画样式。可以是 Color 或 Paint 枚举值或绘图服务器 ID。可选参数。 |
| id | 折线元素的唯一标识符。可选参数。 |
| 扩展 | 一个可选的操作，用于进一步配置折线元素构建器。 |

### 返回值

构建器实例，允许方法链式调用。

### 另请参阅

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
