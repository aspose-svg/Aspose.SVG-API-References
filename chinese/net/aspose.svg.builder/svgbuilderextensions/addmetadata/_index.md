---
title: "SVGBuilderExtensions.AddMetadata"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddMetadata 方法。向构建器添加 metadata 元素配置。metadata 元素用于向 SVG 内容添加元数据"
type: docs
weight: 390
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addmetadata/
---
## SVGBuilderExtensions.AddMetadata<TBuilder,TElement> method

向构建器添加一个 'metadata' 元素配置。'metadata' 元素用于向 SVG 内容添加元数据。

```csharp
public static TBuilder AddMetadata<TBuilder, TElement>(this TBuilder builder, 
    Action<SVGMetadataElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| TElement | 表示 SVG 模型中 'metadata' 元素的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 针对 'metadata' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGMetadataElementBuilder](../../svgmetadataelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
