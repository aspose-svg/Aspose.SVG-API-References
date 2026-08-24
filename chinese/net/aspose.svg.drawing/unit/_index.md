---
title: "Unit 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Drawing.Unit 类。提供计量单位的基类。"
type: docs
weight: 3660
url: /zh/net/aspose.svg.drawing/unit/
---
## Unit class

提供度量单位的基类。

```csharp
public abstract class Unit : IEquatable<Unit>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [UnitType](../../aspose.svg.drawing/unit/unittype/) { get; } | 获取 `Unit` 的单位类型。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.svg.drawing/unit/equals/#equals_1)(*object*) | 确定指定的 Object 是否等于此实例。 |
| virtual [Equals](../../aspose.svg.drawing/unit/equals/#equals)(*Unit*) | 确定指定的 `Unit` 是否等于此实例。 |
| override [GetHashCode](../../aspose.svg.drawing/unit/gethashcode/)() | 返回此实例的哈希码。 |
| override [ToString](../../aspose.svg.drawing/unit/tostring/)() | 返回表示此实例的字符串。 |
| static [FromCentimeters](../../aspose.svg.drawing/unit/fromcentimeters/)(*double*) | 返回一个以厘米为单位表示的 [`Length`](../length/) 对象。 |
| static [FromDegrees](../../aspose.svg.drawing/unit/fromdegrees/)(*double*) | 返回一个以度为单位表示的 [`Angle`](../angle/) 对象。 |
| static [FromDotsPerCentimeters](../../aspose.svg.drawing/unit/fromdotspercentimeters/)(*double*) | 返回一个以每厘米点数表示的 [`Resolution`](../resolution/) 对象。 |
| static [FromDotsPerInch](../../aspose.svg.drawing/unit/fromdotsperinch/)(*double*) | 返回一个 [`Resolution`](../resolution/) 对象，以每英寸点数表示。 |
| static [FromDotsPerPixel](../../aspose.svg.drawing/unit/fromdotsperpixel/)(*double*) | 返回一个 [`Resolution`](../resolution/) 对象，以每像素点数表示。 |
| static [FromGradians](../../aspose.svg.drawing/unit/fromgradians/)(*double*) | 返回一个 [`Angle`](../angle/) 对象，以百分度表示。 |
| static [FromHertz](../../aspose.svg.drawing/unit/fromhertz/)(*double*) | 返回一个 [`Frequency`](../frequency/) 对象，以赫兹表示。 |
| static [FromInches](../../aspose.svg.drawing/unit/frominches/)(*double*) | 返回一个 [`Length`](../length/) 对象，以英寸表示。 |
| static [FromKiloHertz](../../aspose.svg.drawing/unit/fromkilohertz/)(*double*) | 返回一个 [`Frequency`](../frequency/) 对象，以千赫兹表示。 |
| static [FromMillimeters](../../aspose.svg.drawing/unit/frommillimeters/)(*double*) | 返回一个 [`Length`](../length/) 对象，以毫米表示。 |
| static [FromMilliseconds](../../aspose.svg.drawing/unit/frommilliseconds/)(*double*) | 返回一个 [`Time`](../time/) 对象，以毫秒表示。 |
| static [FromPicas](../../aspose.svg.drawing/unit/frompicas/)(*double*) | 返回一个 [`Length`](../length/) 对象，以派卡表示。 |
| static [FromPixels](../../aspose.svg.drawing/unit/frompixels/)(*double*) | 返回一个 [`Length`](../length/) 对象，以像素表示。 |
| static [FromPoints](../../aspose.svg.drawing/unit/frompoints/)(*double*) | 返回一个 [`Length`](../length/) 对象，以点表示。 |
| static [FromQuarterMillimeters](../../aspose.svg.drawing/unit/fromquartermillimeters/)(*double*) | 返回一个 [`Length`](../length/) 对象，以四分之一毫米表示。 |
| static [FromRadians](../../aspose.svg.drawing/unit/fromradians/)(*double*) | 返回一个 [`Angle`](../angle/) 对象，以弧度表示。 |
| static [FromSeconds](../../aspose.svg.drawing/unit/fromseconds/)(*double*) | 返回一个 [`Time`](../time/) 对象，以秒表示。 |
| static [FromTurns](../../aspose.svg.drawing/unit/fromturns/)(*double*) | 返回一个 [`Angle`](../angle/) 对象，以周表示。 |

### 另请参阅

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
