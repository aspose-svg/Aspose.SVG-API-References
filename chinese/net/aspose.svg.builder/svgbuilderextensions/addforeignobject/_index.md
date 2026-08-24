---
title: "SVGBuilderExtensions.AddForeignObject"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddForeignObject 方法。向构建器添加 foreignObject 元素的配置"
type: docs
weight: 310
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addforeignobject/
---
## SVGBuilderExtensions.AddForeignObject<TBuilder> method

向构建器添加一个 'foreignObject' 元素配置。

```csharp
public static TBuilder AddForeignObject<TBuilder>(this TBuilder builder, 
    Action<SVGForeignObjectElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 针对 'foreignObject' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGForeignObjectElementBuilder](../../svgforeignobjectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
