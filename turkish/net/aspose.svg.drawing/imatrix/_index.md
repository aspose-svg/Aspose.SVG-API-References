---
title: "IMatrix Interface"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Drawing.IMatrix interface. Dönüşümler için kullanılan bir matrisi temsil eder"
type: docs
weight: 3500
url: /tr/net/aspose.svg.drawing/imatrix/
---
## IMatrix interface

Dönüşümler için kullanılan bir matrisi temsil eder.

```csharp
public interface IMatrix
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [IsIdentity](../../aspose.svg.drawing/imatrix/isidentity/) { get; } | Bu matrisin birim matris olup olmadığını gösteren bir değer alır. |
| [IsInvertible](../../aspose.svg.drawing/imatrix/isinvertible/) { get; } | Bu matrisin terslenebilir olup olmadığını gösteren bir değer alır. |
| [M11](../../aspose.svg.drawing/imatrix/m11/) { get; set; } | Matrisin birinci satır ve birinci sütunundaki değeri alır veya ayarlar. |
| [M12](../../aspose.svg.drawing/imatrix/m12/) { get; set; } | Matrisin birinci satır ve ikinci sütunundaki değeri alır veya ayarlar. |
| [M21](../../aspose.svg.drawing/imatrix/m21/) { get; set; } | Matrisin ikinci satır ve birinci sütunundaki değeri alır veya ayarlar. |
| [M22](../../aspose.svg.drawing/imatrix/m22/) { get; set; } | Matrisin ikinci satır ve ikinci sütunundaki değeri alır veya ayarlar. |
| [M31](../../aspose.svg.drawing/imatrix/m31/) { get; set; } | Matrisin üçüncü satır ve birinci sütunundaki değeri alır veya ayarlar. |
| [M32](../../aspose.svg.drawing/imatrix/m32/) { get; set; } | Matrisin üçüncü satır ve ikinci sütunundaki değeri alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Clone](../../aspose.svg.drawing/imatrix/clone/)() | Bu matrisin bir kopyasını oluşturur. |
| [GetElements](../../aspose.svg.drawing/imatrix/getelements/)() | Matrisin elemanlarını bir dizi olarak alır. |
| [Invert](../../aspose.svg.drawing/imatrix/invert/)() | Bu matrisi tersine çevirir. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply)(*IMatrix*) | Bu matrisi başka bir matrisle çarpar. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply_1)(*IMatrix, [WebMatrixOrder](../webmatrixorder/)*) | Bu matrisi belirtilen sırada başka bir matrisle çarpar. |
| [Reset](../../aspose.svg.drawing/imatrix/reset/)() | Matris, kimlik matrisine sıfırlanır. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate)(*float*) | Matris, belirtilen açıyla döndürülür. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate_1)(*float, [WebMatrixOrder](../webmatrixorder/)*) | Matris, belirtilen açıyla ve belirtilen sırada döndürülür. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat)(*float, PointF*) | Matris, belirtilen noktada belirtilen açıyla döndürülür. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat_1)(*float, PointF, [WebMatrixOrder](../webmatrixorder/)*) | Matris, belirtilen noktada belirtilen açıyla ve belirtilen sırada döndürülür. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale)(*float, float*) | Matris, belirtilen ölçek faktörleriyle eşit olarak ölçeklendirilir. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Matris, belirtilen ölçek faktörleriyle ve belirtilen sırada ölçeklendirilir. |
| [Skew](../../aspose.svg.drawing/imatrix/skew/)(*float, float*) | Matrise bir eğik dönüşüm uygulanır. |
| [TransformPoint](../../aspose.svg.drawing/imatrix/transformpoint/)(*PointF*) | Bu matris kullanılarak belirtilen nokta dönüştürülür. |
| [TransformPoints](../../aspose.svg.drawing/imatrix/transformpoints/)(*PointF[]*) | Bu matris kullanılarak bir dizi nokta dönüştürülür. |
| [TransformRectangle](../../aspose.svg.drawing/imatrix/transformrectangle/)(*RectangleF*) | Bu matris kullanılarak belirtilen dikdörtgen dönüştürülür. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate)(*float, float*) | Matris, belirtilen ofset değerleriyle kaydırılır. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Matris, belirtilen ofset değerleriyle ve belirtilen sırada kaydırılır. |

### Ayrıca Bakınız

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
