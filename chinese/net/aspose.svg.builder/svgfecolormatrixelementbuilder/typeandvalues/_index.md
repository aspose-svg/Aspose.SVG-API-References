---
title: "SVGFEColorMatrixElementBuilder.TypeAndValues"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGFEColorMatrixElementBuilder TypeAndValues 方法。设置 feColorMatrix 元素的 type 和 values 属性，指定颜色矩阵操作及其参数。"
type: docs
weight: 30
url: /zh/net/aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/
---
## SVGFEColorMatrixElementBuilder.TypeAndValues method

设置 feColorMatrix 元素的 'type' 和 'values' 属性，指定颜色矩阵操作及其参数。

```csharp
public SVGFEColorMatrixElementBuilder TypeAndValues(ColorMatrixOperation type, 
    params double[] values)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | ColorMatrixOperation | ColorMatrixOperation 枚举值，表示颜色矩阵操作的类型。 |
| values | Double[] | 颜色矩阵操作的参数。 |

### 返回值

当前构建器实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 当提供的值不符合指定类型的要求时抛出。 |
| NotSupportedException | 当提供不受支持的矩阵操作类型时抛出。 |

### 另请参阅

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [SVGFEColorMatrixElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
