---
title: "SVGBuilderExtensions.AddClipPath"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddClipPath 方法。向构建器添加 clipPath 元素配置"
type: docs
weight: 80
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addclippath/
---
## SVGBuilderExtensions.AddClipPath<TBuilder> method

向构建器添加一个 'clipPath' 元素配置。

```csharp
public static TBuilder AddClipPath<TBuilder>(this TBuilder builder, 
    Action<SVGClipPathElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 用于 'clipPath' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGClipPathElementBuilder](../../svgclippathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
