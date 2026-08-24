---
title: "SVGBuilderExtensions.AddAnimateMotion"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddAnimateMotion 方法。向构建器添加 animateMotion 元素配置"
type: docs
weight: 40
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addanimatemotion/
---
## SVGBuilderExtensions.AddAnimateMotion<TBuilder> method

向构建器添加一个 'animateMotion' 元素配置。

```csharp
public static TBuilder AddAnimateMotion<TBuilder>(this TBuilder builder, 
    Action<SVGAnimateMotionElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 针对 'animateMotion' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGAnimateMotionElementBuilder](../../svganimatemotionelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationElementBuilder](../../ianimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
