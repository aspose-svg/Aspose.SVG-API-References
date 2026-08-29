---
title: "Интерфейс IMatrix"
second_title: "Aspose.SVG для .NET справочник API"
description: "Интерфейс Aspose.Svg.Drawing.IMatrix. Представляет матрицу, используемую для преобразований"
type: docs
weight: 3500
url: /ru/net/aspose.svg.drawing/imatrix/
---
## IMatrix interface

Представляет матрицу, используемую для преобразований.

```csharp
public interface IMatrix
```

## Свойства

| Имя | Описание |
| --- | --- |
| [IsIdentity](../../aspose.svg.drawing/imatrix/isidentity/) { get; } | Возвращает значение, указывающее, является ли эта матрица единичной. |
| [IsInvertible](../../aspose.svg.drawing/imatrix/isinvertible/) { get; } | Возвращает значение, указывающее, является ли эта матрица обратимой. |
| [M11](../../aspose.svg.drawing/imatrix/m11/) { get; set; } | Получает или задает значение в первой строке и первом столбце матрицы. |
| [M12](../../aspose.svg.drawing/imatrix/m12/) { get; set; } | Получает или задает значение в первой строке и втором столбце матрицы. |
| [M21](../../aspose.svg.drawing/imatrix/m21/) { get; set; } | Получает или задает значение во второй строке и первом столбце матрицы. |
| [M22](../../aspose.svg.drawing/imatrix/m22/) { get; set; } | Получает или задает значение во второй строке и втором столбце матрицы. |
| [M31](../../aspose.svg.drawing/imatrix/m31/) { get; set; } | Получает или задает значение в третьей строке и первом столбце матрицы. |
| [M32](../../aspose.svg.drawing/imatrix/m32/) { get; set; } | Получает или задает значение в третьей строке и втором столбце матрицы. |

## Методы

| Имя | Описание |
| --- | --- |
| [Clone](../../aspose.svg.drawing/imatrix/clone/)() | Создаёт копию этой матрицы. |
| [GetElements](../../aspose.svg.drawing/imatrix/getelements/)() | Получает элементы матрицы в виде массива. |
| [Invert](../../aspose.svg.drawing/imatrix/invert/)() | Инвертирует эту матрицу. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply)(*IMatrix*) | Умножает эту матрицу на другую матрицу. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply_1)(*IMatrix, [WebMatrixOrder](../webmatrixorder/)*) | Умножает эту матрицу на другую матрицу в указанном порядке. |
| [Reset](../../aspose.svg.drawing/imatrix/reset/)() | Сбрасывает матрицу к единичной матрице. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate)(*float*) | Поворачивает матрицу на указанный угол. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate_1)(*float, [WebMatrixOrder](../webmatrixorder/)*) | Поворачивает матрицу на указанный угол в указанном порядке. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat)(*float, PointF*) | Поворачивает матрицу на указанный угол вокруг указанной точки. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat_1)(*float, PointF, [WebMatrixOrder](../webmatrixorder/)*) | Поворачивает матрицу на указанный угол вокруг указанной точки в указанном порядке. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale)(*float, float*) | Масштабирует матрицу на указанные коэффициенты масштабирования равномерно. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Масштабирует матрицу на указанные коэффициенты масштабирования в указанном порядке. |
| [Skew](../../aspose.svg.drawing/imatrix/skew/)(*float, float*) | Применяет к матрице трансформацию наклона. |
| [TransformPoint](../../aspose.svg.drawing/imatrix/transformpoint/)(*PointF*) | Трансформирует указанную точку с помощью этой матрицы. |
| [TransformPoints](../../aspose.svg.drawing/imatrix/transformpoints/)(*PointF[]*) | Трансформирует массив точек с помощью этой матрицы. |
| [TransformRectangle](../../aspose.svg.drawing/imatrix/transformrectangle/)(*RectangleF*) | Трансформирует указанный прямоугольник с помощью этой матрицы. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate)(*float, float*) | Смещает матрицу на указанные значения смещения. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Трансформирует матрицу с указанными значениями смещения в указанном порядке. |

### См. также

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
