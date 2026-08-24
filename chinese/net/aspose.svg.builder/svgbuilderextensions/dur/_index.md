---
title: "SVGBuilderExtensions.Dur"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions Dur 方法。设置 dur 属性，指定动画的持续时间。"
type: docs
weight: 760
url: /zh/net/aspose.svg.builder/svgbuilderextensions/dur/
---
## Dur<TBuilder>(*this TBuilder, TimeSpan*) {#dur_1}

设置 'dur' 属性，指定动画的持续时间。

```csharp
public static TBuilder Dur<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| duration | 动画的持续时间。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dur<TBuilder>(*this TBuilder, [Dur](../../dur/)*) {#dur}

设置 'dur' 属性，指定动画的预定义持续时间类型。

```csharp
public static TBuilder Dur<TBuilder>(this TBuilder builder, Dur value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 动画的预定义持续时间类型。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [Dur](../../dur/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
