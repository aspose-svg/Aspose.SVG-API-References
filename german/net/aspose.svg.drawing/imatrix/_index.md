---
title: "IMatrix Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Drawing.IMatrix Schnittstelle. Stellt eine für Transformationen verwendete Matrix dar."
type: docs
weight: 3500
url: /de/net/aspose.svg.drawing/imatrix/
---
## IMatrix interface

Stellt eine Matrix dar, die für Transformationen verwendet wird.

```csharp
public interface IMatrix
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsIdentity](../../aspose.svg.drawing/imatrix/isidentity/) { get; } | Gibt einen Wert zurück, der angibt, ob diese Matrix die Einheitsmatrix ist. |
| [IsInvertible](../../aspose.svg.drawing/imatrix/isinvertible/) { get; } | Gibt einen Wert zurück, der angibt, ob diese Matrix invertierbar ist. |
| [M11](../../aspose.svg.drawing/imatrix/m11/) { get; set; } | Liest oder setzt den Wert in der ersten Zeile und ersten Spalte der Matrix. |
| [M12](../../aspose.svg.drawing/imatrix/m12/) { get; set; } | Liest oder setzt den Wert in der ersten Zeile und zweiten Spalte der Matrix. |
| [M21](../../aspose.svg.drawing/imatrix/m21/) { get; set; } | Liest oder setzt den Wert in der zweiten Zeile und ersten Spalte der Matrix. |
| [M22](../../aspose.svg.drawing/imatrix/m22/) { get; set; } | Liest oder setzt den Wert in der zweiten Zeile und zweiten Spalte der Matrix. |
| [M31](../../aspose.svg.drawing/imatrix/m31/) { get; set; } | Liest oder setzt den Wert in der dritten Zeile und ersten Spalte der Matrix. |
| [M32](../../aspose.svg.drawing/imatrix/m32/) { get; set; } | Liest oder setzt den Wert in der dritten Zeile und zweiten Spalte der Matrix. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Clone](../../aspose.svg.drawing/imatrix/clone/)() | Erstellt eine Kopie dieser Matrix. |
| [GetElements](../../aspose.svg.drawing/imatrix/getelements/)() | Liefert die Elemente der Matrix als Array. |
| [Invert](../../aspose.svg.drawing/imatrix/invert/)() | Invertiert diese Matrix. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply)(*IMatrix*) | Multipliziert diese Matrix mit einer anderen Matrix. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply_1)(*IMatrix, [WebMatrixOrder](../webmatrixorder/)*) | Multipliziert diese Matrix mit einer anderen Matrix in der angegebenen Reihenfolge. |
| [Reset](../../aspose.svg.drawing/imatrix/reset/)() | Setzt die Matrix auf die Einheitsmatrix zurück. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate)(*float*) | Dreht die Matrix um den angegebenen Winkel. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate_1)(*float, [WebMatrixOrder](../webmatrixorder/)*) | Dreht die Matrix um den angegebenen Winkel in der angegebenen Reihenfolge. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat)(*float, PointF*) | Dreht die Matrix um den angegebenen Winkel um den angegebenen Punkt. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat_1)(*float, PointF, [WebMatrixOrder](../webmatrixorder/)*) | Dreht die Matrix um den angegebenen Winkel um den angegebenen Punkt in der angegebenen Reihenfolge. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale)(*float, float*) | Skaliert die Matrix um die angegebenen Skalierungsfaktoren einheitlich. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Skaliert die Matrix um die angegebenen Skalierungsfaktoren in der angegebenen Reihenfolge. |
| [Skew](../../aspose.svg.drawing/imatrix/skew/)(*float, float*) | Wendet eine Schrägstellungstransformation auf die Matrix an. |
| [TransformPoint](../../aspose.svg.drawing/imatrix/transformpoint/)(*PointF*) | Transformiert den angegebenen Punkt mit dieser Matrix. |
| [TransformPoints](../../aspose.svg.drawing/imatrix/transformpoints/)(*PointF[]*) | Transformiert ein Array von Punkten mit dieser Matrix. |
| [TransformRectangle](../../aspose.svg.drawing/imatrix/transformrectangle/)(*RectangleF*) | Transformiert das angegebene Rechteck mit dieser Matrix. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate)(*float, float*) | Verschiebt die Matrix um die angegebenen Offset-Werte. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Verschiebt die Matrix um die angegebenen Offset-Werte in der angegebenen Reihenfolge. |

### Siehe auch

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
