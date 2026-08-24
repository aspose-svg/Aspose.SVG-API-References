---
title: "SVGBuilderExtensions.ClipPath"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions ClipPath 方法。设置 SVG 元素的 clip-path 属性"
type: docs
weight: 650
url: /zh/net/aspose.svg.builder/svgbuilderextensions/clippath/
---
## SVGBuilderExtensions.ClipPath<TBuilder> method

设置 SVG 元素的 'clip-path' 属性。

```csharp
public static TBuilder ClipPath<TBuilder>(this TBuilder builder, Action<ClipPathBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 用于配置剪切路径的委托。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [ClipPathBuilder](../../clippathbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
