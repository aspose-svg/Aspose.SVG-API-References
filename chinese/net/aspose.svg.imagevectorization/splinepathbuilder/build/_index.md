---
title: "SplinePathBuilder.Build"
second_title: "Aspose.SVG for .NET API 参考"
description: "SplinePathBuilder Build 方法。通过将向心 CatmullRom 样条转换为贝塞尔曲线，在一系列点之间构建平滑路径。此方法确保在每个点之间实现自然平滑的过渡，生成紧随提供的轨迹的 SVG 路径"
type: docs
weight: 50
url: /zh/net/aspose.svg.imagevectorization/splinepathbuilder/build/
---
## SplinePathBuilder.Build method

通过将离心 Catmull–Rom 样条转换为贝塞尔曲线，在一系列点之间构建平滑路径。此方法确保在每个点之间实现自然平滑的过渡，生成紧随提供的 trace 的 SVG 路径。

```csharp
public string Build(IEnumerable<PointF> trace)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| trace | IEnumerable`1 | 要插值为平滑路径的点序列。 |

### 返回值

表示 SVG 路径数据的字符串，包含贝塞尔曲线指令和坐标，以近似向心 Catmull–Rom 样条。

### 另请参阅

* class [SplinePathBuilder](../)
* namespace [Aspose.Svg.ImageVectorization](../../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../../)
