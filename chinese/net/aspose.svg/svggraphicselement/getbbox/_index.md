---
title: "SVGGraphicsElement.GetBBox"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGGraphicsElement GetBBox 方法。返回当前用户空间中的紧凑边界框，即在对所有包含的图形元素的几何体（如果有）应用 transform 属性后的结果，且不包括描边、裁剪、遮罩和滤镜效果。请注意，即使元素尚未渲染，getBBox 也必须返回调用时的实际边界框。"
type: docs
weight: 70
url: /zh/net/aspose.svg/svggraphicselement/getbbox/
---
## SVGGraphicsElement.GetBBox method

返回当前用户坐标空间（即在应用了 ‘transform’ 属性后，如果有的话）中所有包含的图形元素的几何形状的紧凑边界框（不包括描边、裁剪、遮罩和滤镜效果）。请注意，getBBox 必须在调用时返回实际的边界框，即使该元素尚未渲染。

```csharp
public SVGRect GetBBox()
```

### 返回值

一个定义边界框的 SVGRect 对象。

### 另请参阅

* class [SVGRect](../../../aspose.svg.datatypes/svgrect/)
* class [SVGGraphicsElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
