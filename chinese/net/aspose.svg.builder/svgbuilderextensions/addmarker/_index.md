---
title: "SVGBuilderExtensions.AddMarker"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddMarker 方法。向构建器添加标记元素配置"
type: docs
weight: 370
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addmarker/
---
## SVGBuilderExtensions.AddMarker<TBuilder> method

向构建器添加一个 'marker' 元素配置。

```csharp
public static TBuilder AddMarker<TBuilder>(this TBuilder builder, 
    Action<SVGMarkerElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | ‘marker’ 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGMarkerElementBuilder](../../svgmarkerelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
