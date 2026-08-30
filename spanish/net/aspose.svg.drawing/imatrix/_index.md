---
title: "Interfaz IMatrix"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Aspose.Svg.Drawing.IMatrix interface. Representa una matriz utilizada para transformaciones"
type: docs
weight: 3500
url: /es/net/aspose.svg.drawing/imatrix/
---
## IMatrix interface

Representa una matriz utilizada para transformaciones.

```csharp
public interface IMatrix
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsIdentity](../../aspose.svg.drawing/imatrix/isidentity/) { get; } | Obtiene un valor que indica si esta matriz es la matriz identidad. |
| [IsInvertible](../../aspose.svg.drawing/imatrix/isinvertible/) { get; } | Obtiene un valor que indica si esta matriz es invertible. |
| [M11](../../aspose.svg.drawing/imatrix/m11/) { get; set; } | Obtiene o establece el valor en la primera fila y primera columna de la matriz. |
| [M12](../../aspose.svg.drawing/imatrix/m12/) { get; set; } | Obtiene o establece el valor en la primera fila y segunda columna de la matriz. |
| [M21](../../aspose.svg.drawing/imatrix/m21/) { get; set; } | Obtiene o establece el valor en la segunda fila y primera columna de la matriz. |
| [M22](../../aspose.svg.drawing/imatrix/m22/) { get; set; } | Obtiene o establece el valor en la segunda fila y segunda columna de la matriz. |
| [M31](../../aspose.svg.drawing/imatrix/m31/) { get; set; } | Obtiene o establece el valor en la tercera fila y primera columna de la matriz. |
| [M32](../../aspose.svg.drawing/imatrix/m32/) { get; set; } | Obtiene o establece el valor en la tercera fila y segunda columna de la matriz. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../aspose.svg.drawing/imatrix/clone/)() | Crea una copia de esta matriz. |
| [GetElements](../../aspose.svg.drawing/imatrix/getelements/)() | Obtiene los elementos de la matriz como una matriz. |
| [Invert](../../aspose.svg.drawing/imatrix/invert/)() | Invierte esta matriz. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply)(*IMatrix*) | Multiplica esta matriz por otra matriz. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply_1)(*IMatrix, [WebMatrixOrder](../webmatrixorder/)*) | Multiplica esta matriz por otra matriz en el orden especificado. |
| [Reset](../../aspose.svg.drawing/imatrix/reset/)() | Restablece la matriz a la matriz identidad. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate)(*float*) | Rota la matriz por el ángulo especificado. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate_1)(*float, [WebMatrixOrder](../webmatrixorder/)*) | Rota la matriz por el ángulo especificado en el orden especificado. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat)(*float, PointF*) | Rota la matriz por el ángulo especificado alrededor del punto especificado. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat_1)(*float, PointF, [WebMatrixOrder](../webmatrixorder/)*) | Rota la matriz por el ángulo especificado alrededor del punto especificado en el orden especificado. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale)(*float, float*) | Escala la matriz por los factores de escala especificados de forma uniforme. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Escala la matriz por los factores de escala especificados en el orden especificado. |
| [Skew](../../aspose.svg.drawing/imatrix/skew/)(*float, float*) | Aplica una transformación de sesgo a la matriz. |
| [TransformPoint](../../aspose.svg.drawing/imatrix/transformpoint/)(*PointF*) | Transforma el punto especificado usando esta matriz. |
| [TransformPoints](../../aspose.svg.drawing/imatrix/transformpoints/)(*PointF[]*) | Transforma una matriz de puntos usando esta matriz. |
| [TransformRectangle](../../aspose.svg.drawing/imatrix/transformrectangle/)(*RectangleF*) | Transforma el rectángulo especificado usando esta matriz. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate)(*float, float*) | Traslada la matriz por los valores de desplazamiento especificados. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Traslada la matriz por los valores de desplazamiento especificados en el orden especificado. |

### Ver también

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
