---
title: "IMatrix Interface"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Aspose.Svg.Drawing.IMatrix interface. Rappresenta una matrice utilizzata per le trasformazioni"
type: docs
weight: 3500
url: /it/net/aspose.svg.drawing/imatrix/
---
## IMatrix interface

Rappresenta una matrice utilizzata per le trasformazioni.

```csharp
public interface IMatrix
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IsIdentity](../../aspose.svg.drawing/imatrix/isidentity/) { get; } | Ottiene un valore che indica se questa matrice è la matrice identità. |
| [IsInvertible](../../aspose.svg.drawing/imatrix/isinvertible/) { get; } | Ottiene un valore che indica se questa matrice è invertibile. |
| [M11](../../aspose.svg.drawing/imatrix/m11/) { get; set; } | Ottiene o imposta il valore nella prima riga e nella prima colonna della matrice. |
| [M12](../../aspose.svg.drawing/imatrix/m12/) { get; set; } | Ottiene o imposta il valore nella prima riga e nella seconda colonna della matrice. |
| [M21](../../aspose.svg.drawing/imatrix/m21/) { get; set; } | Ottiene o imposta il valore nella seconda riga e nella prima colonna della matrice. |
| [M22](../../aspose.svg.drawing/imatrix/m22/) { get; set; } | Ottiene o imposta il valore nella seconda riga e nella seconda colonna della matrice. |
| [M31](../../aspose.svg.drawing/imatrix/m31/) { get; set; } | Ottiene o imposta il valore nella terza riga e nella prima colonna della matrice. |
| [M32](../../aspose.svg.drawing/imatrix/m32/) { get; set; } | Ottiene o imposta il valore nella terza riga e nella seconda colonna della matrice. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Clone](../../aspose.svg.drawing/imatrix/clone/)() | Crea una copia di questa matrice. |
| [GetElements](../../aspose.svg.drawing/imatrix/getelements/)() | Ottiene gli elementi della matrice come array. |
| [Invert](../../aspose.svg.drawing/imatrix/invert/)() | Inverte questa matrice. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply)(*IMatrix*) | Moltiplica questa matrice per un'altra matrice. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply_1)(*IMatrix, [WebMatrixOrder](../webmatrixorder/)*) | Moltiplica questa matrice per un'altra matrice nell'ordine specificato. |
| [Reset](../../aspose.svg.drawing/imatrix/reset/)() | Ripristina la matrice alla matrice identità. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate)(*float*) | Ruota la matrice di un angolo specificato. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate_1)(*float, [WebMatrixOrder](../webmatrixorder/)*) | Ruota la matrice di un angolo specificato nell'ordine specificato. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat)(*float, PointF*) | Ruota la matrice di un angolo specificato attorno al punto specificato. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat_1)(*float, PointF, [WebMatrixOrder](../webmatrixorder/)*) | Ruota la matrice di un angolo specificato attorno al punto specificato nell'ordine specificato. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale)(*float, float*) | Scala la matrice dei fattori di scala specificati in modo uniforme. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Scala la matrice dei fattori di scala specificati nell'ordine specificato. |
| [Skew](../../aspose.svg.drawing/imatrix/skew/)(*float, float*) | Applica una trasformazione di inclinazione alla matrice. |
| [TransformPoint](../../aspose.svg.drawing/imatrix/transformpoint/)(*PointF*) | Trasforma il punto specificato usando questa matrice. |
| [TransformPoints](../../aspose.svg.drawing/imatrix/transformpoints/)(*PointF[]*) | Trasforma un array di punti usando questa matrice. |
| [TransformRectangle](../../aspose.svg.drawing/imatrix/transformrectangle/)(*RectangleF*) | Trasforma il rettangolo specificato usando questa matrice. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate)(*float, float*) | Trasla la matrice dei valori di offset specificati. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Trasla la matrice dei valori di offset specificati nell'ordine specificato. |

### Vedi anche

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
