---
title: "SVGBuilderExtensions.FillOpacity"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions FillOpacity 方法。设置 SVG 元素的 fill-opacity 属性。值必须在 0.0（完全透明）到 1.0（完全不透明）之间"
type: docs
weight: 820
url: /zh/net/aspose.svg.builder/svgbuilderextensions/fillopacity/
---
## SVGBuilderExtensions.FillOpacity<TBuilder> method

为 SVG 元素设置 'fill-opacity' 属性。值必须在 0.0（完全透明）和 1.0（完全不透明）之间。

```csharp
public static TBuilder FillOpacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| opacity | 要设置的不透明度值。 |

### 返回值

用于链式调用的构建器实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 如果不透明度不在有效范围内则抛出此异常。 |

### 另请参阅

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
