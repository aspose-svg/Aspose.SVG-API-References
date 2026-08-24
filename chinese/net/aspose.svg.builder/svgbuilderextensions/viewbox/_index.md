---
title: "SVGBuilderExtensions.ViewBox"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions ViewBox 方法。设置 SVG 元素的 viewBox 属性。"
type: docs
weight: 2300
url: /zh/net/aspose.svg.builder/svgbuilderextensions/viewbox/
---
## SVGBuilderExtensions.ViewBox<TBuilder> method

为 SVG 元素设置 'viewBox' 属性。

```csharp
public static TBuilder ViewBox<TBuilder>(this TBuilder builder, double minX, double minY, 
    double width, double height)
    where TBuilder : ISVGElementBuilder, IViewBoxAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| minX | viewBox 的最小 X 坐标。 |
| minY | viewBox 的最小 Y 坐标。 |
| width | viewBox 的宽度。 |
| height | viewBox 的高度。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IViewBoxAttributeSetter](../../iviewboxattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
