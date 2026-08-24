---
title: "CalcMode 枚举"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.CalcMode 枚举。指定 SVG 动画中值插值的计算模式"
type: docs
weight: 90
url: /zh/net/aspose.svg.builder/calcmode/
---
## CalcMode enumeration

指定 SVG 动画中插值计算的模式。

```csharp
public enum CalcMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Discrete | `0` | 动画在数值之间跳变，不进行任何插值。 |
| Linear | `1` | 动画数值在整个动画持续期间线性插值。 |
| Paced | `2` | 动画的节奏被设置为使整个动画的进度保持均匀。 |
| Spline | `3` | 动画使用三次贝塞尔样条曲线来插值数值。 |

## 备注

计算模式决定了 SVG 动画在整个动画过程中如何在数值之间过渡。不同的模式可用于创建各种效果并控制动画的节奏和流畅度。

### 另请参阅

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
