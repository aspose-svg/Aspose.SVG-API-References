---
title: "ShapeRendering 枚举。"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.ShapeRendering 枚举。指定 SVG 元素的形状渲染模式。"
type: docs
weight: 1720
url: /zh/net/aspose.svg.builder/shaperendering/
---
## ShapeRendering enumeration

指定 SVG 元素的形状渲染模式。

```csharp
public enum ShapeRendering
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Auto | `0` | 浏览器在渲染形状时在速度、平滑度和几何精度之间进行权衡。 |
| OptimizeSpeed | `1` | 浏览器更强调渲染速度而非几何精度和平滑度。此模式可能导致更快的渲染，但形状精度降低。 |
| CrispEdges | `2` | 浏览器尝试保留锐利的边缘和角落。此模式对于渲染具有直线和边缘的图形非常有用。 |
| GeometricPrecision | `3` | 浏览器在渲染时强调几何精度，代价是速度。此模式适用于对几何精度要求高的高质量渲染。 |

### 另请参阅

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
