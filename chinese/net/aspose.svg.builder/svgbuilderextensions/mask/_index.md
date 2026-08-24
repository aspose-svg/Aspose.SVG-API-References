---
title: "SVGBuilderExtensions.Mask"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions Mask 方法。使用自定义遮罩配置为 SVG 元素设置 mask 属性"
type: docs
weight: 1150
url: /zh/net/aspose.svg.builder/svgbuilderextensions/mask/
---
## SVGBuilderExtensions.Mask<TBuilder> method

使用自定义遮罩配置，设置 SVG 元素的 'mask' 属性。

```csharp
public static TBuilder Mask<TBuilder>(this TBuilder builder, Action<MaskBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 用于配置遮罩的委托。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [MaskBuilder](../../maskbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
