---
title: "SVGBuilderExtensions.RefX"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions RefX 方法。设置 SVG 元素的 refX 属性。"
type: docs
weight: 1930
url: /zh/net/aspose.svg.builder/svgbuilderextensions/refx/
---
## RefX<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#refx_1}

设置 SVG 元素的 'refX' 属性。

```csharp
public static TBuilder RefX<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRefCoordinatesAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| value | 参考 X 坐标。 |
| type | 长度单位的类型（默认是像素）。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRefCoordinatesAttributeSetter](../../irefcoordinatesattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RefX<TBuilder>(*this TBuilder, [HorizontalPosition](../../horizontalposition/)*) {#refx}

使用预定义的水平位置设置 SVG 元素的 'refX' 属性。

```csharp
public static TBuilder RefX<TBuilder>(this TBuilder builder, HorizontalPosition value)
    where TBuilder : ISVGElementBuilder, IRefCoordinatesAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| value | 预定义的水平位置。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [HorizontalPosition](../../horizontalposition/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRefCoordinatesAttributeSetter](../../irefcoordinatesattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
