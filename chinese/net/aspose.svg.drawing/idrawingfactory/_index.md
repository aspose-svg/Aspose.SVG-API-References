---
title: "IDrawingFactory 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Drawing.IDrawingFactory 接口。表示一个用于创建绘图相关对象的工厂"
type: docs
weight: 3460
url: /zh/net/aspose.svg.drawing/idrawingfactory/
---
## IDrawingFactory interface

表示用于创建绘图相关对象的工厂。

```csharp
public interface IDrawingFactory : IDisposable
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateInterpolationColor](../../aspose.svg.drawing/idrawingfactory/createinterpolationcolor/)(*Color, float*) | 使用指定的颜色和位置创建插值颜色。 |
| [CreateLinearGradientBrush](../../aspose.svg.drawing/idrawingfactory/createlineargradientbrush/)(*RectangleF, IInterpolationColor[]*) | 使用指定的参数创建线性渐变画刷。 |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix)() | 创建一个新的单位矩阵。 |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_1)(*[IMatrix](../imatrix/)*) | 创建一个与指定矩阵具有相同内容的新矩阵。 |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_2)(*float, float, float, float, float, float*) | 使用指定的元素创建一个新矩阵。 |
| [CreateSolidBrush](../../aspose.svg.drawing/idrawingfactory/createsolidbrush/)(*Color*) | 使用指定的颜色创建实心画刷。 |
| [CreateTextureBrush](../../aspose.svg.drawing/idrawingfactory/createtexturebrush/)(*byte[]*) | 使用指定的参数创建纹理画刷。 |

### 另请参阅

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
