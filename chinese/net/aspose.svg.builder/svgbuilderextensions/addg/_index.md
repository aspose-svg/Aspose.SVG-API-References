---
title: "SVGBuilderExtensions.AddG"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddG 方法。向构建器添加 g 组元素的配置。"
type: docs
weight: 320
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addg/
---
## SVGBuilderExtensions.AddG<TBuilder> method

向构建器添加一个 'g'（组）元素配置。

```csharp
public static TBuilder AddG<TBuilder>(this TBuilder builder, Action<SVGGElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 针对 'g' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGGElementBuilder](../../svggelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
