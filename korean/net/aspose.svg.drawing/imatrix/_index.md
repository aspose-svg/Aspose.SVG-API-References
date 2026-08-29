---
title: "IMatrix 인터페이스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Drawing.IMatrix 인터페이스. 변환에 사용되는 행렬을 나타냅니다"
type: docs
weight: 3500
url: /ko/net/aspose.svg.drawing/imatrix/
---
## IMatrix interface

변환에 사용되는 행렬을 나타냅니다.

```csharp
public interface IMatrix
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [IsIdentity](../../aspose.svg.drawing/imatrix/isidentity/) { get; } | 이 행렬이 항등 행렬인지 여부를 나타내는 값을 가져옵니다. |
| [IsInvertible](../../aspose.svg.drawing/imatrix/isinvertible/) { get; } | 이 행렬이 역행 가능한지 여부를 나타내는 값을 가져옵니다. |
| [M11](../../aspose.svg.drawing/imatrix/m11/) { get; set; } | 행렬의 첫 번째 행 첫 번째 열에 있는 값을 가져오거나 설정합니다. |
| [M12](../../aspose.svg.drawing/imatrix/m12/) { get; set; } | 행렬의 첫 번째 행 두 번째 열에 있는 값을 가져오거나 설정합니다. |
| [M21](../../aspose.svg.drawing/imatrix/m21/) { get; set; } | 행렬의 두 번째 행 첫 번째 열에 있는 값을 가져오거나 설정합니다. |
| [M22](../../aspose.svg.drawing/imatrix/m22/) { get; set; } | 행렬의 두 번째 행 두 번째 열에 있는 값을 가져오거나 설정합니다. |
| [M31](../../aspose.svg.drawing/imatrix/m31/) { get; set; } | 행렬의 세 번째 행 첫 번째 열에 있는 값을 가져오거나 설정합니다. |
| [M32](../../aspose.svg.drawing/imatrix/m32/) { get; set; } | 행렬의 세 번째 행 두 번째 열에 있는 값을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Clone](../../aspose.svg.drawing/imatrix/clone/)() | 이 행렬의 복사본을 생성합니다. |
| [GetElements](../../aspose.svg.drawing/imatrix/getelements/)() | 행렬의 요소를 배열로 가져옵니다. |
| [Invert](../../aspose.svg.drawing/imatrix/invert/)() | 이 행렬을 역전시킵니다. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply)(*IMatrix*) | 이 행렬을 다른 행렬과 곱합니다. |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply_1)(*IMatrix, [WebMatrixOrder](../webmatrixorder/)*) | 이 행렬을 지정된 순서대로 다른 행렬과 곱합니다. |
| [Reset](../../aspose.svg.drawing/imatrix/reset/)() | 행렬을 단위 행렬로 재설정합니다. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate)(*float*) | 지정된 각도만큼 행렬을 회전시킵니다. |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate_1)(*float, [WebMatrixOrder](../webmatrixorder/)*) | 지정된 순서대로 지정된 각도만큼 행렬을 회전시킵니다. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat)(*float, PointF*) | 지정된 점을 중심으로 지정된 각도만큼 행렬을 회전시킵니다. |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat_1)(*float, PointF, [WebMatrixOrder](../webmatrixorder/)*) | 지정된 순서대로 지정된 점을 중심으로 지정된 각도만큼 행렬을 회전시킵니다. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale)(*float, float*) | 지정된 스케일 팩터를 균일하게 적용하여 행렬을 확대/축소합니다. |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | 지정된 순서대로 지정된 스케일 팩터를 적용하여 행렬을 확대/축소합니다. |
| [Skew](../../aspose.svg.drawing/imatrix/skew/)(*float, float*) | 행렬에 기울이기 변환을 적용합니다. |
| [TransformPoint](../../aspose.svg.drawing/imatrix/transformpoint/)(*PointF*) | 이 행렬을 사용하여 지정된 점을 변환합니다. |
| [TransformPoints](../../aspose.svg.drawing/imatrix/transformpoints/)(*PointF[]*) | 이 행렬을 사용하여 점 배열을 변환합니다. |
| [TransformRectangle](../../aspose.svg.drawing/imatrix/transformrectangle/)(*RectangleF*) | 이 행렬을 사용하여 지정된 사각형을 변환합니다. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate)(*float, float*) | 지정된 오프셋 값만큼 행렬을 평행 이동합니다. |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | 지정된 순서대로 지정된 오프셋 값만큼 행렬을 평행 이동합니다. |

### 또 보기

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
