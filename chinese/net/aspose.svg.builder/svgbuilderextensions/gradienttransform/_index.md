---
title: "SVGBuilderExtensions.GradientTransform"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions GradientTransform 方法。为渐变元素设置 gradientTransform 属性。"
type: docs
weight: 980
url: /zh/net/aspose.svg.builder/svgbuilderextensions/gradienttransform/
---
## SVGBuilderExtensions.GradientTransform<TBuilder> method

为渐变元素设置 'gradientTransform' 属性。

```csharp
public static TBuilder GradientTransform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 属性应用于的 SVG 元素构建器。 |
| 配置 | 用于配置 SVG 变换构建器的函数。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
