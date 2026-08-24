---
title: "SVGBuilderExtensions.Transform"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions Transform 方法。为 SVG 元素设置 transform 属性"
type: docs
weight: 2260
url: /zh/net/aspose.svg.builder/svgbuilderextensions/transform/
---
## SVGBuilderExtensions.Transform<TBuilder> method

为 SVG 元素设置 'transform' 属性。

```csharp
public static TBuilder Transform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, ITransformAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 用于配置 SVG 转换的函数。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITransformAttributeSetter](../../itransformattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
