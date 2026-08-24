---
title: "SVGBuilderExtensions.GradientUnits"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions GradientUnits 方法。为渐变元素设置 gradientUnits 属性"
type: docs
weight: 990
url: /zh/net/aspose.svg.builder/svgbuilderextensions/gradientunits/
---
## SVGBuilderExtensions.GradientUnits<TBuilder> method

为渐变元素设置 'gradientUnits' 属性。

```csharp
public static TBuilder GradientUnits<TBuilder>(this TBuilder builder, CoordinateUnits units)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 属性应用于的 SVG 元素构建器。 |
| 单位 | 渐变的坐标单位（userSpaceOnUse 或 objectBoundingBox）。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [CoordinateUnits](../../coordinateunits/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
