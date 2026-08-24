---
title: "SVGBuilderExtensions.AddBuilder"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddBuilder 方法。将现有的 SVG 元素构建器添加到当前的 SVG 元素构建器中。此方法用于将预定义的 SVG 元素构建器包含到当前构建器中"
type: docs
weight: 60
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addbuilder/
---
## SVGBuilderExtensions.AddBuilder<TBuilder,TElementBuilder> method

向当前 SVG 元素构建器添加已有的 SVG 元素构建器。此方法用于将预定义的 SVG 元素构建器包含到当前构建器中。

```csharp
public static TBuilder AddBuilder<TBuilder, TElementBuilder>(this TBuilder builder, 
    TElementBuilder elementBuilder)
    where TBuilder : ISVGElementBuilder
    where TElementBuilder : ISVGElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| TElementBuilder | 要配置的 SVG 元素构建器的类型。TElementBuilder 必须实现 ISVGElementBuilder。 |
| 构建器 | 要向其添加其他元素构建器的 SVG 元素构建器。 |
| elementBuilder | 要添加的 SVG 元素构建器。 |

### 返回值

用于方法链的原始 SVG 元素构建器。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
