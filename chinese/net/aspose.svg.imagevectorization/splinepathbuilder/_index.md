---
title: "SplinePathBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.ImageVectorization.SplinePathBuilder 类。SplinePathBuilder 类旨在通过将离心 CatmullRom 样条转换为贝塞尔曲线来构建平滑路径。它提供了一种方法，可生成在一组点之间平滑插值的路径，在保持点的精度与曲线的平滑度之间取得平衡。"
type: docs
weight: 4230
url: /zh/net/aspose.svg.imagevectorization/splinepathbuilder/
---
## SplinePathBuilder class

`SplinePathBuilder` 类旨在通过将离心 Catmull–Rom 样条转换为贝塞尔曲线来构建平滑路径。它提供了一种方法，可生成在一组点之间平滑插值的路径，在保持点的精度与曲线的平滑度之间取得平衡。

```csharp
public class SplinePathBuilder : IPathBuilder
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SplinePathBuilder](splinepathbuilder/#constructor)() | 初始化 `SplinePathBuilder` 类的新实例。 |
| [SplinePathBuilder](splinepathbuilder/#constructor_2)(*float*) | 初始化 `SplinePathBuilder` 类的新实例。 |
| [SplinePathBuilder](splinepathbuilder/#constructor_1)(*[IImageTraceSmoother](../iimagetracesmoother/), [IImageTraceSimplifier](../iimagetracesimplifier/), float*) | 初始化 `SplinePathBuilder` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Tension](../../aspose.svg.imagevectorization/splinepathbuilder/tension/) { get; set; } | 张力的取值会影响曲线在（插值）控制点处的弯曲程度。它必须在 0 到 1 的范围内。任何高于或低于该范围的值将分别对齐到该范围的最大值和最小值。 |
| [TraceSimplifier](../../aspose.svg.imagevectorization/splinepathbuilder/tracesimplifier/) { get; set; } | 获取或设置 trace 简化器。 |
| [TraceSmoother](../../aspose.svg.imagevectorization/splinepathbuilder/tracesmoother/) { get; set; } | 获取或设置 trace 平滑器。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Build](../../aspose.svg.imagevectorization/splinepathbuilder/build/)(*IEnumerable&lt;PointF&gt;*) | 通过将离心 Catmull–Rom 样条转换为贝塞尔曲线，在一系列点之间构建平滑路径。此方法确保在每个点之间实现自然平滑的过渡，生成紧随提供的 trace 的 SVG 路径。 |

### 另请参阅

* interface [IPathBuilder](../ipathbuilder/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
