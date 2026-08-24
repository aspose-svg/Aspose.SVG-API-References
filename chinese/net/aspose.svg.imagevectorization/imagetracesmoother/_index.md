---
title: "ImageTraceSmoother 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.ImageVectorization.ImageTraceSmoother 类。ImageTraceSimplifier 类负责平滑由一系列跟踪点近似的曲线中的点数。此类实现最近邻方法。"
type: docs
weight: 4200
url: /zh/net/aspose.svg.imagevectorization/imagetracesmoother/
---
## ImageTraceSmoother class

该 ImageTraceSimplifier 类负责平滑由一系列追踪点近似的曲线中的点数。该类实现了最近邻方法。

```csharp
public class ImageTraceSmoother : IImageTraceSmoother
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageTraceSmoother](imagetracesmoother/#constructor)() | 初始化 `ImageTraceSmoother` 类的新实例。 |
| [ImageTraceSmoother](imagetracesmoother/#constructor_1)(*int*) | 初始化 `ImageTraceSmoother` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Extent](../../aspose.svg.imagevectorization/imagetracesmoother/extent/) { get; set; } | 获取或设置查询点考虑的区域范围。该值必须在 1 到 20 的范围内。任何超出此范围的值将相应地对齐到该范围的最小值或最大值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Smooth](../../aspose.svg.imagevectorization/imagetracesmoother/smooth/)(*IEnumerable&lt;PointF&gt;*) | 平滑跟踪。 |

### 另请参阅

* interface [IImageTraceSmoother](../iimagetracesmoother/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
