---
title: "SVGBuilderExtensions.Rotate"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions Rotate 方法。为文本内容的各个字符或段落设置旋转角度"
type: docs
weight: 2000
url: /zh/net/aspose.svg.builder/svgbuilderextensions/rotate/
---
## Rotate<TBuilder>(*this TBuilder, params double[]*) {#rotate_1}

为文本内容的各个字符或段落设置旋转角度。

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| values | 以度为单位的旋转角度数组。 |

### 返回值

用于链式调用的构建器实例。

## 备注

此方法使用多个值设置 'rotate' 属性，允许对每个字符或文本段落进行单独旋转。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Rotate<TBuilder>(*this TBuilder, double*) {#rotate}

为整个文本内容设置单一旋转角度。

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, double value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 以度为单位的旋转角度。 |

### 返回值

用于链式调用的构建器实例。

## 备注

此方法使用单个值设置 'rotate' 属性，对所有文本内容应用相同的旋转角度。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
