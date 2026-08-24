---
title: "BezierPathBuilder.Build"
second_title: "Aspose.SVG for .NET API 参考"
description: "BezierPathBuilder Build 方法。根据一系列跟踪点构建优化的贝塞尔路径。该方法使用直线和曲线段的组合将给定的跟踪近似为贝塞尔曲线。它旨在在确保路径紧密贴合原始跟踪的同时，最小化段的数量"
type: docs
weight: 50
url: /zh/net/aspose.svg.imagevectorization/bezierpathbuilder/build/
---
## BezierPathBuilder.Build method

从一系列 trace 点构建优化的贝塞尔路径。该方法使用直线段和曲线段的组合，用贝塞尔曲线近似给定的 trace，旨在最小化段数，同时确保路径紧密贴合原始 trace。

```csharp
public string Build(IEnumerable<PointF> trace)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| trace | IEnumerable`1 | 定义待近似跟踪的点序列。 |

### 返回值

表示 SVG 路径数据的字符串。该数据由一系列定义贝塞尔路径的命令和坐标组成，以最小的复杂度紧密近似输入的跟踪。

### 另请参阅

* class [BezierPathBuilder](../)
* namespace [Aspose.Svg.ImageVectorization](../../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../../)
