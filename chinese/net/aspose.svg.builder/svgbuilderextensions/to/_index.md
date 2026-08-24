---
title: "SVGBuilderExtensions.To"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions To 方法。使用指定的长度类型设置定义动画结束值的 to 属性"
type: docs
weight: 2250
url: /zh/net/aspose.svg.builder/svgbuilderextensions/to/
---
## SVGBuilderExtensions.To<TBuilder> method

设置 'to' 属性，定义具有指定长度类型的动画结束值。

```csharp
public static TBuilder To<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 动画的结束值。 |
| type | 'to' 值的长度类型。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
