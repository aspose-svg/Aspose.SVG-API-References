---
title: "Antarmuka IMatrix"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Antarmuka Aspose.Svg.Drawing.IMatrix. Mewakili sebuah matriks yang digunakan untuk transformasi."
type: docs
weight: 3500
url: /id/net/aspose.svg.drawing/imatrix/
---
## IMatrix interface

Mewakili matriks yang digunakan untuk transformasi.

```csharp
public interface IMatrix
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [IsIdentity](../../aspose.svg.drawing/imatrix/isidentity/) { get; } | Mendapatkan nilai yang menunjukkan apakah matriks ini adalah matriks identitas. |
| [IsInvertible](../../aspose.svg.drawing/imatrix/isinvertible/) { get; } | Mendapatkan nilai yang menunjukkan apakah matriks ini dapat dibalik. |
| [M11](../../aspose.svg.drawing/imatrix/m11/) { get; set; } | Mendapatkan atau mengatur nilai pada baris pertama dan kolom pertama matriks. |
| [M12](../../aspose.svg.drawing/imatrix/m12/) { get; set; } | Mendapatkan atau mengatur nilai pada baris pertama dan kolom kedua matriks. |
| [M21](../../aspose.svg.drawing/imatrix/m21/) { get; set; } | Mendapatkan atau mengatur nilai pada baris kedua dan kolom pertama matriks. |
| [M22](../../aspose.svg.drawing/imatrix/m22/) { get; set; } | Mendapatkan atau mengatur nilai pada baris kedua dan kolom kedua matriks. |
| [M31](../../aspose.svg.drawing/imatrix/m31/) { get; set; } | Mendapatkan atau mengatur nilai pada baris ketiga dan kolom pertama matriks. |
| [M32](../../aspose.svg.drawing/imatrix/m32/) { get; set; } | Mendapatkan atau mengatur nilai pada baris ketiga dan kolom kedua matriks. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clone](../../aspose.svg.drawing/imatrix/clone/)() | Membuat salinan dari matriks ini. |
| [GetElements](../../aspose.svg.drawing/imatrix/getelements/)() | Mendapatkan elemen-elemen matriks sebagai array. |
| [Invert](../../aspose.svg.drawing/imatrix/invert/)() | Membalik matriks ini. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply)(*IMatrix*) | Mengalikan matriks ini dengan matriks lain. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply_1)(*IMatrix, [WebMatrixOrder](../webmatrixorder/)*) | Mengalikan matriks ini dengan matriks lain dalam urutan yang ditentukan. |
| [Reset](../../aspose.svg.drawing/imatrix/reset/)() | Mengatur ulang matriks ke matriks identitas. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate)(*float*) | Memutar matriks dengan sudut yang ditentukan. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate_1)(*float, [WebMatrixOrder](../webmatrixorder/)*) | Memutar matriks dengan sudut yang ditentukan dalam urutan yang ditentukan. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat)(*float, PointF*) | Memutar matriks dengan sudut yang ditentukan sekitar titik yang ditentukan. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat_1)(*float, PointF, [WebMatrixOrder](../webmatrixorder/)*) | Memutar matriks dengan sudut yang ditentukan sekitar titik yang ditentukan dalam urutan yang ditentukan. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale)(*float, float*) | Menskalakan matriks dengan faktor skala yang ditentukan secara seragam. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Menskalakan matriks dengan faktor skala yang ditentukan dalam urutan yang ditentukan. |
| [Skew](../../aspose.svg.drawing/imatrix/skew/)(*float, float*) | Menerapkan transformasi miring pada matriks. |
| [TransformPoint](../../aspose.svg.drawing/imatrix/transformpoint/)(*PointF*) | Mengubah titik yang ditentukan menggunakan matriks ini. |
| [TransformPoints](../../aspose.svg.drawing/imatrix/transformpoints/)(*PointF[]*) | Mengubah array titik menggunakan matriks ini. |
| [TransformRectangle](../../aspose.svg.drawing/imatrix/transformrectangle/)(*RectangleF*) | Mengubah persegi panjang yang ditentukan menggunakan matriks ini. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate)(*float, float*) | Mentranslasi matriks dengan nilai offset yang ditentukan. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Menerjemahkan matriks dengan nilai offset yang ditentukan dalam urutan yang ditentukan. |

### Lihat Juga

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
