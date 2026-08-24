---
title: "SVGBuilderExtensions.Fill"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions Fill 方法。设置 fill 属性，定义动画在其活动持续时间之外如何应用样式。"
type: docs
weight: 810
url: /zh/net/aspose.svg.builder/svgbuilderextensions/fill/
---
## Fill<TBuilder>(*this TBuilder, [AnimationFill](../../animationfill/)*) {#fill}

设置 'fill' 属性，定义动画在其活动持续时间之外如何应用样式。

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, AnimationFill value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 动画的填充行为。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [AnimationFill](../../animationfill/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Fill<TBuilder>(*this TBuilder, Action&lt;PaintBuilder&gt;*) {#fill_2}

使用自定义配置设置 SVG 元素的 'fill' 属性。

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, Action<PaintBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 用于配置 PaintBuilder 的委托。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [PaintBuilder](../../paintbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Fill<TBuilder>(*this TBuilder, Color*) {#fill_3}

使用颜色设置 SVG 元素的 'fill' 属性。

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, Color color)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 颜色 | 用于设置填充的颜色。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Fill<TBuilder>(*this TBuilder, [Paint](../../paint/)*) {#fill_1}

使用预定义的 Paint 枚举值设置 SVG 元素的 'fill' 属性。

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, Paint paint)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| paint | 要设置的 Paint 枚举值。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [Paint](../../paint/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
