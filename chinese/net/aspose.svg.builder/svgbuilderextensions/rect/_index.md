---
title: "SVGBuilderExtensions.Rect"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions Rect 方法。设置 SVG 元素的 x、y、width 和 height 属性以定义矩形"
type: docs
weight: 1920
url: /zh/net/aspose.svg.builder/svgbuilderextensions/rect/
---
## SVGBuilderExtensions.Rect<TBuilder> method

设置 SVG 元素的 'x'、'y'、'width' 和 'height' 属性，以定义矩形。

```csharp
public static TBuilder Rect<TBuilder>(this TBuilder builder, double x, double y, double width, 
    double height, LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRectAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| x | 矩形的 x 坐标。 |
| y | 矩形的 y 坐标。 |
| width | 矩形的宽度。 |
| height | 矩形的高度。 |
| type | 所有尺寸的长度度量类型（默认是像素）。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRectAttributeSetter](../../irectattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
