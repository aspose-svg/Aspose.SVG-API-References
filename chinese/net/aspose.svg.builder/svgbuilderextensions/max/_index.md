---
title: "SVGBuilderExtensions.Max"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions Max 方法。设置 max 属性，指定动画的最大持续时间。"
type: docs
weight: 1160
url: /zh/net/aspose.svg.builder/svgbuilderextensions/max/
---
## Max<TBuilder>(*this TBuilder, TimeSpan*) {#max_1}

设置 'max' 属性，指定动画的最大持续时间。

```csharp
public static TBuilder Max<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| duration | 动画的最大持续时间。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Max<TBuilder>(*this TBuilder, [Media](../../media/)*) {#max}

设置 'max' 属性，指定动画的预定义最大持续时间条件。

```csharp
public static TBuilder Max<TBuilder>(this TBuilder builder, Media value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 动画的预定义最大持续时间条件。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [Media](../../media/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
