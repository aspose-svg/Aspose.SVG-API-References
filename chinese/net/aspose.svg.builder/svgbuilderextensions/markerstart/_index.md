---
title: "SVGBuilderExtensions.MarkerStart"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions MarkerStart 方法。为 SVG 元素设置 marker-start 属性，指定路径起始处的标记"
type: docs
weight: 1140
url: /zh/net/aspose.svg.builder/svgbuilderextensions/markerstart/
---
## MarkerStart<TBuilder>(*this TBuilder, string*) {#markerstart_1}

设置 SVG 元素的 'marker-start' 属性，指定路径起点的标记。

```csharp
public static TBuilder MarkerStart<TBuilder>(this TBuilder builder, string markerId)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| markerId | 要使用的标记的 ID。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## MarkerStart<TBuilder>(*this TBuilder, [MarkerPos](../../markerpos/)*) {#markerstart}

使用预定义的标记位置，设置 SVG 元素的 'marker-start' 属性。

```csharp
public static TBuilder MarkerStart<TBuilder>(this TBuilder builder, MarkerPos value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| value | 要设置的标记位置值。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [MarkerPos](../../markerpos/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
