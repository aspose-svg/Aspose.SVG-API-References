---
title: "SVGBuilderExtensions.Filter"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions Filter 方法。设置 SVG 元素的 filter 属性，使用自定义配置"
type: docs
weight: 840
url: /zh/net/aspose.svg.builder/svgbuilderextensions/filter/
---
## SVGBuilderExtensions.Filter<TBuilder> method

使用自定义配置为 SVG 元素设置 'filter' 属性。

```csharp
public static TBuilder Filter<TBuilder>(this TBuilder builder, 
    Action<FilterValueListBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 用于配置 FilterValueListBuilder 的委托。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [FilterValueListBuilder](../../filtervaluelistbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
