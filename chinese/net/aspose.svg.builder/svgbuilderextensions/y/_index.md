---
title: "SVGBuilderExtensions.Y"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions Y 方法。设置 SVG 元素的 y 属性"
type: docs
weight: 2400
url: /zh/net/aspose.svg.builder/svgbuilderextensions/y/
---
## Y<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#y_1}

为 SVG 元素设置 'y' 属性。

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IYAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| value | ‘y’ 属性的值。 |
| type | 长度测量的类型（默认是像素）。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IYAttributeSetter](../../iyattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Y<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#y}

设置 'y' 属性以在 y 轴上定位文本内容。

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| type | 这些值的长度单位类型。 |
| values | y 轴位置值。 |

### 返回值

用于链式调用的构建器实例。

## 备注

此方法设置 ‘y’ 属性，该属性决定文本元素的垂直位置。

### 另请参阅

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
