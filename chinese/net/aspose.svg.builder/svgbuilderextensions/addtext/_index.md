---
title: "SVGBuilderExtensions.AddText"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddText 方法。向构建器添加文本元素配置。"
type: docs
weight: 530
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addtext/
---
## AddText<TBuilder>(*this TBuilder, Action&lt;SVGTextElementBuilder&gt;*) {#addtext}

向构建器添加一个 'text' 元素配置。

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, 
    Action<SVGTextElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 用于 'text' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddText<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, FontStyle?, string, FontWeight?, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGTextElementBuilder&gt;*) {#addtext_1}

向 SVG 构建器添加一个带有指定内容和属性的 'text' 元素。

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, string content, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> fontSize = null, FontStyle? fontStyle = default, 
    string fontFamily = null, FontWeight? fontWeight = default, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGTextElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型，允许链式调用。 |
| 构建器 | 将向其添加 'text' 元素的构建器实例。 |
| 内容 | 将在 'text' 元素中显示的文本内容。 |
| x | 文本元素的 x 坐标。可以是 double 值或 double 与 LengthType 的元组。 |
| y | 文本元素的 y 坐标。可以是 double 值或 double 与 LengthType 的元组。 |
| fontSize | 文本的字体大小。可以是 double 值或 double 与 LengthType 的元组。 |
| fontStyle | 文本的字体样式（例如，normal、italic、oblique）。 |
| fontFamily | 文本的字体族（例如，Arial、Verdana）。 |
| fontWeight | 字体的粗细（例如，normal、bold）。 |
| fill | 文本的填充颜色或绘制样式。可以是 Color、Paint 枚举值或绘图服务器 ID。 |
| stroke | 文本的描边颜色或绘制样式。可以是 Color、Paint 枚举值或绘图服务器 ID。 |
| id | 文本元素的唯一标识符。 |
| 扩展 | 可选操作，用于进一步配置文本元素构建器。 |

### 返回值

用于链式添加或配置的构建器实例。

### 另请参阅

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [FontStyle](../../fontstyle/)
* enum [FontWeight](../../fontweight/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
