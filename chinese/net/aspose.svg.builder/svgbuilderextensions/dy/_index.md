---
title: "SVGBuilderExtensions.Dy"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions Dy 方法。为文本内容设置多个垂直调整值"
type: docs
weight: 780
url: /zh/net/aspose.svg.builder/svgbuilderextensions/dy/
---
## Dy<TBuilder>(*this TBuilder, double[], [LengthType](../../lengthtype/)*) {#dy_1}

为文本内容设置多个垂直调整值。

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double[] values, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| values | 垂直调整值的数组。 |
| type | 这些值的长度单位类型。 |

### 返回值

用于链式调用的构建器实例。

## 备注

此方法使用多个值设置 'dy' 属性，允许对每个字符或文本段落进行单独的垂直调整。

### 另请参阅

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dy<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dy}

为文本内容设置单个垂直调整值。

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 垂直调整值。 |
| type | 该值的长度单位类型。 |

### 返回值

用于链式调用的构建器实例。

## 备注

此方法使用单个值设置 'dy' 属性，调整文本内容的垂直位置。

### 另请参阅

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
