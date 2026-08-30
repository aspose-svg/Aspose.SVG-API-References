---
title: "IMatrix-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Drawing.IMatrix-gränssnitt. Representerar en matris som används för transformationer."
type: docs
weight: 3500
url: /sv/net/aspose.svg.drawing/imatrix/
---
## IMatrix interface

Representerar en matris som används för transformationer.

```csharp
public interface IMatrix
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [IsIdentity](../../aspose.svg.drawing/imatrix/isidentity/) { get; } | Hämtar ett värde som indikerar om denna matris är identitetsmatrisen. |
| [IsInvertible](../../aspose.svg.drawing/imatrix/isinvertible/) { get; } | Hämtar ett värde som indikerar om denna matris är inverterbar. |
| [M11](../../aspose.svg.drawing/imatrix/m11/) { get; set; } | Hämtar eller anger värdet i den första raden och första kolumnen i matrisen. |
| [M12](../../aspose.svg.drawing/imatrix/m12/) { get; set; } | Hämtar eller anger värdet i den första raden och andra kolumnen i matrisen. |
| [M21](../../aspose.svg.drawing/imatrix/m21/) { get; set; } | Hämtar eller anger värdet i den andra raden och första kolumnen i matrisen. |
| [M22](../../aspose.svg.drawing/imatrix/m22/) { get; set; } | Hämtar eller anger värdet i den andra raden och andra kolumnen i matrisen. |
| [M31](../../aspose.svg.drawing/imatrix/m31/) { get; set; } | Hämtar eller anger värdet i den tredje raden och första kolumnen i matrisen. |
| [M32](../../aspose.svg.drawing/imatrix/m32/) { get; set; } | Hämtar eller anger värdet i den tredje raden och andra kolumnen i matrisen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../aspose.svg.drawing/imatrix/clone/)() | Skapar en kopia av denna matris. |
| [GetElements](../../aspose.svg.drawing/imatrix/getelements/)() | Hämtar elementen i matrisen som en array. |
| [Invert](../../aspose.svg.drawing/imatrix/invert/)() | Inverterar denna matris. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply)(*IMatrix*) | Multiplicerar denna matris med en annan matris. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply_1)(*IMatrix, [WebMatrixOrder](../webmatrixorder/)*) | Multiplicerar denna matris med en annan matris i den angivna ordningen. |
| [Reset](../../aspose.svg.drawing/imatrix/reset/)() | Återställer matrisen till identitetsmatrisen. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate)(*float*) | Roterar matrisen med den angivna vinkeln. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate_1)(*float, [WebMatrixOrder](../webmatrixorder/)*) | Roterar matrisen med den angivna vinkeln i den angivna ordningen. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat)(*float, PointF*) | Roterar matrisen med den angivna vinkeln runt den angivna punkten. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat_1)(*float, PointF, [WebMatrixOrder](../webmatrixorder/)*) | Roterar matrisen med den angivna vinkeln runt den angivna punkten i den angivna ordningen. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale)(*float, float*) | Skalar matrisen med de angivna skalningsfaktorerna jämnt. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Skalar matrisen med de angivna skalningsfaktorerna i den angivna ordningen. |
| [Skew](../../aspose.svg.drawing/imatrix/skew/)(*float, float*) | Tillämpar en skev transformation på matrisen. |
| [TransformPoint](../../aspose.svg.drawing/imatrix/transformpoint/)(*PointF*) | Transformerar den angivna punkten med hjälp av denna matris. |
| [TransformPoints](../../aspose.svg.drawing/imatrix/transformpoints/)(*PointF[]*) | Transformerar en array av punkter med hjälp av denna matris. |
| [TransformRectangle](../../aspose.svg.drawing/imatrix/transformrectangle/)(*RectangleF*) | Transformerar den angivna rektangeln med hjälp av denna matris. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate)(*float, float*) | Förflyttar matrisen med de angivna förskjutningsvärdena. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Förflyttar matrisen med de angivna förskjutningsvärdena i den angivna ordningen. |

### Se även

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
