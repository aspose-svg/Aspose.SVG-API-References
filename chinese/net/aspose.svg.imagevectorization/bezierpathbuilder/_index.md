---
title: "BezierPathBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.ImageVectorization.BezierPathBuilder 类。BezierPathBuilder 类负责从给定的一组点构建贝塞尔路径。它使用贝塞尔曲线近似点的 trace，优化段数以紧密匹配原始 trace，同时最小化复杂度。"
type: docs
weight: 4150
url: /zh/net/aspose.svg.imagevectorization/bezierpathbuilder/
---
## BezierPathBuilder class

`BezierPathBuilder` 类负责从给定的一组点构建贝塞尔路径。它使用贝塞尔曲线近似点的 trace，优化段数以紧密匹配原始 trace，同时最小化复杂度。

```csharp
public class BezierPathBuilder : IPathBuilder
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BezierPathBuilder](bezierpathbuilder/)() | 初始化 `BezierPathBuilder` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ErrorThreshold](../../aspose.svg.imagevectorization/bezierpathbuilder/errorthreshold/) { get; set; } | 获取或设置误差阈值。此参数定义点到拟合曲线的最大偏差。默认值为 30。 |
| [MaxIterations](../../aspose.svg.imagevectorization/bezierpathbuilder/maxiterations/) { get; set; } | 获取或设置误差阈值。此参数定义最小二乘近似方法的迭代次数。默认值为 30。 |
| [TraceSmoother](../../aspose.svg.imagevectorization/bezierpathbuilder/tracesmoother/) { get; set; } | 获取或设置 trace 平滑器。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Build](../../aspose.svg.imagevectorization/bezierpathbuilder/build/)(*IEnumerable&lt;PointF&gt;*) | 从一系列 trace 点构建优化的贝塞尔路径。该方法使用直线段和曲线段的组合，用贝塞尔曲线近似给定的 trace，旨在最小化段数，同时确保路径紧密贴合原始 trace。 |

### 另请参阅

* interface [IPathBuilder](../ipathbuilder/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
