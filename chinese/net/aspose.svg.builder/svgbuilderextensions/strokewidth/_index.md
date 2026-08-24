---
title: "SVGBuilderExtensions.StrokeWidth"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions StrokeWidth 方法。设置 SVG 元素的 stroke-width 属性，定义描边的宽度。"
type: docs
weight: 2150
url: /zh/net/aspose.svg.builder/svgbuilderextensions/strokewidth/
---
## SVGBuilderExtensions.StrokeWidth<TBuilder> method

为 SVG 元素设置 'stroke-width' 属性，定义描边的宽度。

```csharp
public static TBuilder StrokeWidth<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| value | 描边宽度值。 |
| type | 描边宽度的单位类型。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
