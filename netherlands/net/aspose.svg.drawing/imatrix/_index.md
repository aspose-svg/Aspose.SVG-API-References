---
title: "IMatrix interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Drawing.IMatrix interface. Vertegenwoordigt een matrix die wordt gebruikt voor transformaties"
type: docs
weight: 3500
url: /nl/net/aspose.svg.drawing/imatrix/
---
## IMatrix interface

Stelt een matrix voor die wordt gebruikt voor transformaties.

```csharp
public interface IMatrix
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [IsIdentity](../../aspose.svg.drawing/imatrix/isidentity/) { get; } | Haalt een waarde op die aangeeft of deze matrix de eenheidsmatrix is. |
| [IsInvertible](../../aspose.svg.drawing/imatrix/isinvertible/) { get; } | Haalt een waarde op die aangeeft of deze matrix inverteerbaar is. |
| [M11](../../aspose.svg.drawing/imatrix/m11/) { get; set; } | Haalt de waarde op of stelt de waarde in de eerste rij en eerste kolom van de matrix in. |
| [M12](../../aspose.svg.drawing/imatrix/m12/) { get; set; } | Haalt de waarde op of stelt de waarde in de eerste rij en tweede kolom van de matrix in. |
| [M21](../../aspose.svg.drawing/imatrix/m21/) { get; set; } | Haalt de waarde op of stelt de waarde in de tweede rij en eerste kolom van de matrix in. |
| [M22](../../aspose.svg.drawing/imatrix/m22/) { get; set; } | Haalt de waarde op of stelt de waarde in de tweede rij en tweede kolom van de matrix in. |
| [M31](../../aspose.svg.drawing/imatrix/m31/) { get; set; } | Haalt de waarde op of stelt de waarde in de derde rij en eerste kolom van de matrix in. |
| [M32](../../aspose.svg.drawing/imatrix/m32/) { get; set; } | Haalt de waarde op of stelt de waarde in de derde rij en tweede kolom van de matrix in. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Clone](../../aspose.svg.drawing/imatrix/clone/)() | Maakt een kopie van deze matrix. |
| [GetElements](../../aspose.svg.drawing/imatrix/getelements/)() | Haalt de elementen van de matrix op als een array. |
| [Invert](../../aspose.svg.drawing/imatrix/invert/)() | Keert deze matrix om. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply)(*IMatrix*) | Vermenigvuldigt deze matrix met een andere matrix. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply_1)(*IMatrix, [WebMatrixOrder](../webmatrixorder/)*) | Vermenigvuldigt deze matrix met een andere matrix in de opgegeven volgorde. |
| [Reset](../../aspose.svg.drawing/imatrix/reset/)() | Stelt de matrix opnieuw in op de eenheidsmatrix. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate)(*float*) | Roteert de matrix met de opgegeven hoek. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate_1)(*float, [WebMatrixOrder](../webmatrixorder/)*) | Roteert de matrix met de opgegeven hoek in de opgegeven volgorde. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat)(*float, PointF*) | Roteert de matrix met de opgegeven hoek rond het opgegeven punt. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat_1)(*float, PointF, [WebMatrixOrder](../webmatrixorder/)*) | Roteert de matrix met de opgegeven hoek rond het opgegeven punt in de opgegeven volgorde. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale)(*float, float*) | Schaalt de matrix met de opgegeven schaalfactoren uniform. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Schaalt de matrix met de opgegeven schaalfactoren in de opgegeven volgorde. |
| [Skew](../../aspose.svg.drawing/imatrix/skew/)(*float, float*) | Past een scheeftransformatie toe op de matrix. |
| [TransformPoint](../../aspose.svg.drawing/imatrix/transformpoint/)(*PointF*) | Transformeert het opgegeven punt met behulp van deze matrix. |
| [TransformPoints](../../aspose.svg.drawing/imatrix/transformpoints/)(*PointF[]*) | Transformeert een array van punten met behulp van deze matrix. |
| [TransformRectangle](../../aspose.svg.drawing/imatrix/transformrectangle/)(*RectangleF*) | Transformeert de opgegeven rechthoek met behulp van deze matrix. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate)(*float, float*) | Verschuift de matrix met de opgegeven offsetwaarden. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Vertaalt de matrix met de opgegeven offsetwaarden in de opgegeven volgorde. |

### Zie ook

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
