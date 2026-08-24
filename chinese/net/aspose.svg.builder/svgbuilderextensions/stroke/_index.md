---
title: "SVGBuilderExtensions.Stroke"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions Stroke 方法。使用自定义绘画配置为 SVG 元素设置 stroke 属性"
type: docs
weight: 2080
url: /zh/net/aspose.svg.builder/svgbuilderextensions/stroke/
---
## Stroke<TBuilder>(*this TBuilder, Action&lt;PaintBuilder&gt;*) {#stroke_1}

使用自定义绘画配置为 SVG 元素设置 'stroke' 属性。

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Action<PaintBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 用于配置绘画的委托。 |

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

## Stroke<TBuilder>(*this TBuilder, Color*) {#stroke_2}

使用特定颜色为 SVG 元素设置 'stroke' 属性。

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Color color)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 颜色 | 用于描边的颜色。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Stroke<TBuilder>(*this TBuilder, [Paint](../../paint/)*) {#stroke}

使用预定义的绘画值为 SVG 元素设置 'stroke' 属性。

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Paint paint)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| paint | 要设置的绘画值。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [Paint](../../paint/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
