---
title: "IMatrix 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Drawing.IMatrix 接口。表示用于变换的矩阵"
type: docs
weight: 3500
url: /zh/net/aspose.svg.drawing/imatrix/
---
## IMatrix interface

表示用于变换的矩阵。

```csharp
public interface IMatrix
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [IsIdentity](../../aspose.svg.drawing/imatrix/isidentity/) { get; } | 获取一个值，指示此矩阵是否为单位矩阵。 |
| [IsInvertible](../../aspose.svg.drawing/imatrix/isinvertible/) { get; } | 获取一个值，指示此矩阵是否可逆。 |
| [M11](../../aspose.svg.drawing/imatrix/m11/) { get; set; } | 获取或设置矩阵第一行第一列的值。 |
| [M12](../../aspose.svg.drawing/imatrix/m12/) { get; set; } | 获取或设置矩阵第一行第二列的值。 |
| [M21](../../aspose.svg.drawing/imatrix/m21/) { get; set; } | 获取或设置矩阵第二行第一列的值。 |
| [M22](../../aspose.svg.drawing/imatrix/m22/) { get; set; } | 获取或设置矩阵第二行第二列的值。 |
| [M31](../../aspose.svg.drawing/imatrix/m31/) { get; set; } | 获取或设置矩阵第三行第一列的值。 |
| [M32](../../aspose.svg.drawing/imatrix/m32/) { get; set; } | 获取或设置矩阵第三行第二列的值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../aspose.svg.drawing/imatrix/clone/)() | 创建此矩阵的副本。 |
| [GetElements](../../aspose.svg.drawing/imatrix/getelements/)() | 获取矩阵的元素数组。 |
| [Invert](../../aspose.svg.drawing/imatrix/invert/)() | 对该矩阵求逆。 |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply)(*IMatrix*) | 将此矩阵乘以另一个矩阵。 |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply_1)(*IMatrix, [WebMatrixOrder](../webmatrixorder/)*) | 按指定顺序将此矩阵乘以另一个矩阵。 |
| [Reset](../../aspose.svg.drawing/imatrix/reset/)() | 将矩阵重置为单位矩阵。 |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate)(*float*) | 按指定角度旋转矩阵。 |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate_1)(*float, [WebMatrixOrder](../webmatrixorder/)*) | 按指定顺序按指定角度旋转矩阵。 |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat)(*float, PointF*) | 围绕指定点按指定角度旋转矩阵。 |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat_1)(*float, PointF, [WebMatrixOrder](../webmatrixorder/)*) | 按指定顺序围绕指定点按指定角度旋转矩阵。 |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale)(*float, float*) | 按指定比例因子均匀缩放矩阵。 |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | 按指定顺序按指定比例因子缩放矩阵。 |
| [Skew](../../aspose.svg.drawing/imatrix/skew/)(*float, float*) | 对矩阵应用倾斜变换。 |
| [TransformPoint](../../aspose.svg.drawing/imatrix/transformpoint/)(*PointF*) | 使用此矩阵转换指定点。 |
| [TransformPoints](../../aspose.svg.drawing/imatrix/transformpoints/)(*PointF[]*) | 使用此矩阵转换点数组。 |
| [TransformRectangle](../../aspose.svg.drawing/imatrix/transformrectangle/)(*RectangleF*) | 使用此矩阵转换指定矩形。 |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate)(*float, float*) | 通过指定的偏移值平移矩阵。 |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | 在指定的顺序中，通过指定的偏移值平移矩阵。 |

### 另请参阅

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
