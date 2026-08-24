---
title: "SVGBuilderExtensions.AddPattern"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddPattern 方法。向构建器添加模式元素配置"
type: docs
weight: 410
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addpattern/
---
## AddPattern<TBuilder>(*this TBuilder, Action&lt;SVGPatternElementBuilder&gt;*) {#addpattern}

向构建器添加一个 'pattern' 元素配置。

```csharp
public static TBuilder AddPattern<TBuilder>(this TBuilder builder, 
    Action<SVGPatternElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 用于 'pattern' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGPatternElementBuilder](../../svgpatternelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPattern<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, string, string, Action&lt;SVGPatternElementBuilder&gt;*) {#addpattern_1}

向 SVG 构建器添加一个 'pattern' 元素，指定图案内容的坐标系统和单位。

```csharp
public static TBuilder AddPattern<TBuilder>(this TBuilder builder, CoordinateUnits? patternUnits, 
    CoordinateUnits? patternContentUnits, string href = null, string id = null, 
    Action<SVGPatternElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型，便于流式 API 使用。 |
| 构建器 | 将向其添加 'pattern' 元素的 SVG 构建器实例。 |
| patternUnits | 指定图案的坐标系。可选参数。 |
| patternContentUnits | 指定图案内部内容的坐标系。可选参数。 |
| href | 对另一个图案的引用（如适用）。可选参数。 |
| id | 图案元素的唯一标识符。可选参数。 |
| 扩展 | 用于进一步配置图案元素构建器的可选操作。 |

### 返回值

构建器实例，允许方法链式调用。

### 另请参阅

* enum [CoordinateUnits](../../coordinateunits/)
* class [SVGPatternElementBuilder](../../svgpatternelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
