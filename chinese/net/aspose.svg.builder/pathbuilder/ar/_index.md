---
title: "PathBuilder.Ar"
second_title: "Aspose.SVG for .NET API 参考"
description: "PathBuilder Ar 方法。向路径数据添加相对椭圆弧曲线命令"
type: docs
weight: 40
url: /zh/net/aspose.svg.builder/pathbuilder/ar/
---
## PathBuilder.Ar method

向路径数据添加相对的 “Elliptical Arc Curve” 命令。

```csharp
public PathBuilder Ar(double r1, double r2, double angle, bool largeArcFlag, bool sweepFlag, 
    double x, double y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| r1 | Double | 相对于当前坐标的椭圆的 x 半径。 |
| r2 | Double | 相对于当前坐标的椭圆的 y 半径。 |
| angle | Double | 相对于当前坐标的椭圆旋转角度（以度为单位）。 |
| largeArcFlag | Boolean | 指示弧线是否应大于或等于 180 度的标志。 |
| sweepFlag | Boolean | 指示弧线是否应沿正角方向绘制的标志。 |
| x | Double | 相对于当前坐标的弧线终点的 x 坐标。 |
| y | Double | 相对于当前坐标的弧线终点的 y 坐标。 |

### 返回值

当前 PathBuilder 实例。

### 另请参阅

* class [PathBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
