---
title: "SVGBuilderExtensions.Height"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions Height 方法。设置 SVG 元素的 height 属性。"
type: docs
weight: 1000
url: /zh/net/aspose.svg.builder/svgbuilderextensions/height/
---
## SVGBuilderExtensions.Height<TBuilder> method

为 SVG 元素设置 'height' 属性。

```csharp
public static TBuilder Height<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IHeightAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| value | ‘height’ 属性的值。 |
| type | 长度测量的类型（默认是像素）。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IHeightAttributeSetter](../../iheightattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
