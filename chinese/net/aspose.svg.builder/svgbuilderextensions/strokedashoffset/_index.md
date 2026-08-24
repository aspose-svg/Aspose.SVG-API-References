---
title: "SVGBuilderExtensions.StrokeDashoffset"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions StrokeDashoffset 方法。设置 SVG 元素的 stroke-dashoffset 属性，定义描边虚线数组起始的偏移量。"
type: docs
weight: 2100
url: /zh/net/aspose.svg.builder/svgbuilderextensions/strokedashoffset/
---
## SVGBuilderExtensions.StrokeDashoffset<TBuilder> method

为 SVG 元素设置 'stroke-dashoffset' 属性，定义描边虚线数组起始的偏移量。

```csharp
public static TBuilder StrokeDashoffset<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| value | 虚线偏移值。 |
| type | 偏移值的单位类型。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
