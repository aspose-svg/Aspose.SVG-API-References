---
title: "SVGBuilderExtensions.AddPath"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddPath 方法。向构建器添加路径元素配置"
type: docs
weight: 400
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addpath/
---
## AddPath<TBuilder>(*this TBuilder, Action&lt;SVGPathElementBuilder&gt;*) {#addpath_2}

向构建器添加一个 'path' 元素配置。

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, 
    Action<SVGPathElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 针对 'path' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPath<TBuilder>(*this TBuilder, OneOf&lt;string, Action&lt;PathBuilder&gt;&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPathElementBuilder&gt;*) {#addpath}

向 SVG 构建器添加一个 'path' 元素，指定其路径数据和样式。

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, 
    OneOf<string, Action<PathBuilder>> d, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGPathElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型，便于流式 API 使用。 |
| 构建器 | 将向其添加 'path' 元素的 SVG 构建器实例。 |
| d | OneOf 类型，可以是表示路径数据的字符串，或配置 PathBuilder 的操作。 |
| fill | 路径的填充颜色或绘制样式。可以是 Color、Paint 枚举值或绘图服务器 ID。可选参数。 |
| stroke | 路径的描边颜色或绘制样式。可以是 Color、Paint 枚举值或绘图服务器 ID。可选参数。 |
| id | 路径元素的唯一标识符。可选参数。 |
| 扩展 | 用于进一步配置路径元素构建器的可选操作。 |

### 返回值

构建器实例，允许方法链式调用。

### 另请参阅

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* class [PathBuilder](../../pathbuilder/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPath<TBuilder>(*this TBuilder, Action&lt;PathBuilder&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPathElementBuilder&gt;*) {#addpath_1}

AddPath 的重载，接受一个操作以直接配置 PathBuilder。

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, Action<PathBuilder> d, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPathElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型，便于流式 API 使用。 |
| 构建器 | 将向其添加 'path' 元素的 SVG 构建器实例。 |
| d | 配置 PathBuilder 以定义路径数据的操作。 |
| fill | 路径的填充颜色或绘制样式。可以是 Color、Paint 枚举值或绘图服务器 ID。可选参数。 |
| stroke | 路径的描边颜色或绘制样式。可以是 Color、Paint 枚举值或绘图服务器 ID。可选参数。 |
| id | 路径元素的唯一标识符。可选参数。 |
| 扩展 | 用于进一步配置路径元素构建器的可选操作。 |

### 返回值

构建器实例，允许方法链式调用。

### 另请参阅

* class [PathBuilder](../../pathbuilder/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
