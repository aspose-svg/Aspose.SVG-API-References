---
title: "SVGBuilderExtensions.SetPreserveAspectRatio"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions SetPreserveAspectRatio 方法。设置 SVG 元素的 preserveAspectRatio 属性"
type: docs
weight: 2020
url: /zh/net/aspose.svg.builder/svgbuilderextensions/setpreserveaspectratio/
---
## SVGBuilderExtensions.SetPreserveAspectRatio<TBuilder> method

为 SVG 元素设置 'preserveAspectRatio' 属性。

```csharp
public static TBuilder SetPreserveAspectRatio<TBuilder>(this TBuilder builder, 
    AspectRatioAlign align, AspectRatioScaling meetOrSlice = AspectRatioScaling.Meet)
    where TBuilder : ISVGElementBuilder, IPreserveAspectRatioAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| align | 纵横比的对齐设置。 |
| meetOrSlice | 指定纵横比的保持方式（默认是 'Meet'）。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [AspectRatioAlign](../../aspectratioalign/)
* enum [AspectRatioScaling](../../aspectratioscaling/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../../ipreserveaspectratioattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
