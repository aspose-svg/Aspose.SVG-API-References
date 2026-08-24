---
title: "SVGBuilderExtensions.From"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions From 方法。设置 from 属性，定义动画的起始值以及指定的长度类型。"
type: docs
weight: 960
url: /zh/net/aspose.svg.builder/svgbuilderextensions/from/
---
## SVGBuilderExtensions.From<TBuilder> method

设置 'from' 属性，使用指定的长度类型定义动画的起始值。

```csharp
public static TBuilder From<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 动画的起始值。 |
| type | ‘from’ 值的长度类型。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
