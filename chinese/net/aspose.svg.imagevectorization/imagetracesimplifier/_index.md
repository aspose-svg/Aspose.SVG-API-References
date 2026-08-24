---
title: "ImageTraceSimplifier 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.ImageVectorization.ImageTraceSimplifier 类。ImageTraceSimplifier 类负责减少由一系列跟踪点近似的曲线中的点数。"
type: docs
weight: 4190
url: /zh/net/aspose.svg.imagevectorization/imagetracesimplifier/
---
## ImageTraceSimplifier class

该 ImageTraceSimplifier 类负责在由一系列追踪点近似的曲线中减少点的数量。

```csharp
public class ImageTraceSimplifier : IImageTraceSimplifier
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageTraceSimplifier](imagetracesimplifier/#constructor)() | 初始化 `ImageTraceSimplifier` 类的新实例。 |
| [ImageTraceSimplifier](imagetracesimplifier/#constructor_1)(*float*) | 初始化 `ImageTraceSimplifier` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Tolerance](../../aspose.svg.imagevectorization/imagetracesimplifier/tolerance/) { get; set; } | 容差值决定了允许从跟踪中消除点的最大误差容限。该值必须在 0 到 4 的范围内。任何超出此范围的值将相应地对齐到该范围的最小值或最大值。默认值为 0.3。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Simplify](../../aspose.svg.imagevectorization/imagetracesimplifier/simplify/)(*IEnumerable&lt;PointF&gt;*) | 减少跟踪点列表中的点数。 |

### 另请参阅

* interface [IImageTraceSimplifier](../iimagetracesimplifier/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
