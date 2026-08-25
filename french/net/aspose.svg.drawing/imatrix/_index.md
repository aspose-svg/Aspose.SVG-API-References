---
title: "Interface IMatrix"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Aspose.Svg.Drawing.IMatrix interface. Représente une matrice utilisée pour les transformations"
type: docs
weight: 3500
url: /fr/net/aspose.svg.drawing/imatrix/
---
## IMatrix interface

Représente une matrice utilisée pour les transformations.

```csharp
public interface IMatrix
```

## Propriétés

| Nom | Description |
| --- | --- |
| [IsIdentity](../../aspose.svg.drawing/imatrix/isidentity/) { get; } | Obtient une valeur indiquant si cette matrice est la matrice identité. |
| [IsInvertible](../../aspose.svg.drawing/imatrix/isinvertible/) { get; } | Obtient une valeur indiquant si cette matrice est inversible. |
| [M11](../../aspose.svg.drawing/imatrix/m11/) { get; set; } | Obtient ou définit la valeur de la première ligne et première colonne de la matrice. |
| [M12](../../aspose.svg.drawing/imatrix/m12/) { get; set; } | Obtient ou définit la valeur de la première ligne et deuxième colonne de la matrice. |
| [M21](../../aspose.svg.drawing/imatrix/m21/) { get; set; } | Obtient ou définit la valeur dans la deuxième ligne et la première colonne de la matrice. |
| [M22](../../aspose.svg.drawing/imatrix/m22/) { get; set; } | Obtient ou définit la valeur dans la deuxième ligne et la deuxième colonne de la matrice. |
| [M31](../../aspose.svg.drawing/imatrix/m31/) { get; set; } | Obtient ou définit la valeur dans la troisième ligne et la première colonne de la matrice. |
| [M32](../../aspose.svg.drawing/imatrix/m32/) { get; set; } | Obtient ou définit la valeur dans la troisième ligne et la deuxième colonne de la matrice. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../aspose.svg.drawing/imatrix/clone/)() | Crée une copie de cette matrice. |
| [GetElements](../../aspose.svg.drawing/imatrix/getelements/)() | Obtient les éléments de la matrice sous forme de tableau. |
| [Invert](../../aspose.svg.drawing/imatrix/invert/)() | Inverse cette matrice. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply)(*IMatrix*) | Multiplie cette matrice par une autre matrice. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply_1)(*IMatrix, [WebMatrixOrder](../webmatrixorder/)*) | Multiplie cette matrice par une autre matrice dans l'ordre spécifié. |
| [Reset](../../aspose.svg.drawing/imatrix/reset/)() | Réinitialise la matrice à la matrice identité. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate)(*float*) | Tourne la matrice de l'angle spécifié. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate_1)(*float, [WebMatrixOrder](../webmatrixorder/)*) | Tourne la matrice de l'angle spécifié dans l'ordre spécifié. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat)(*float, PointF*) | Tourne la matrice de l'angle spécifié autour du point spécifié. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat_1)(*float, PointF, [WebMatrixOrder](../webmatrixorder/)*) | Tourne la matrice de l'angle spécifié autour du point spécifié dans l'ordre spécifié. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale)(*float, float*) | Redimensionne la matrice par les facteurs d'échelle spécifiés de manière uniforme. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Redimensionne la matrice par les facteurs d'échelle spécifiés dans l'ordre spécifié. |
| [Skew](../../aspose.svg.drawing/imatrix/skew/)(*float, float*) | Applique une transformation de cisaillement à la matrice. |
| [TransformPoint](../../aspose.svg.drawing/imatrix/transformpoint/)(*PointF*) | Transforme le point spécifié en utilisant cette matrice. |
| [TransformPoints](../../aspose.svg.drawing/imatrix/transformpoints/)(*PointF[]*) | Transforme un tableau de points en utilisant cette matrice. |
| [TransformRectangle](../../aspose.svg.drawing/imatrix/transformrectangle/)(*RectangleF*) | Transforme le rectangle spécifié en utilisant cette matrice. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate)(*float, float*) | Translater la matrice des valeurs de décalage spécifiées. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Translater la matrice des valeurs de décalage spécifiées dans l'ordre spécifié. |

### Voir aussi

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
