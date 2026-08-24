---
title: "SVGBuilderExtensions.KeySplines"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions KeySplines 方法。设置 keySplines 属性，指定动画节奏的控制点。"
type: docs
weight: 1060
url: /zh/net/aspose.svg.builder/svgbuilderextensions/keysplines/
---
## SVGBuilderExtensions.KeySplines<TBuilder> method

设置 'keySplines' 属性，指定动画节奏的控制点。

```csharp
public static TBuilder KeySplines<TBuilder>(this TBuilder builder, 
    Action<AnimationSplineBuilder> buildSplines)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| buildSplines | 用于构建样条配置的操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [AnimationSplineBuilder](../../animationsplinebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
