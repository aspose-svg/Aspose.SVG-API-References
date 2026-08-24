---
title: "SVGBuilderExtensions.TextLength"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions TextLength 方法。设置文本内容的精确长度"
type: docs
weight: 2220
url: /zh/net/aspose.svg.builder/svgbuilderextensions/textlength/
---
## SVGBuilderExtensions.TextLength<TBuilder> method

设置文本内容的精确长度。

```csharp
public static TBuilder TextLength<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 文本的长度。 |
| type | 该值的长度单位类型。 |

### 返回值

用于链式调用的构建器实例。

## 备注

此方法设置 'textLength' 属性，指定文本内容的期望长度，可能会覆盖自然文本长度。

### 另请参阅

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
