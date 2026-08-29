---
title: "IDrawingFactory 인터페이스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Drawing.IDrawingFactory 인터페이스. 그리기 관련 객체를 생성하는 팩토리를 나타냅니다"
type: docs
weight: 3460
url: /ko/net/aspose.svg.drawing/idrawingfactory/
---
## IDrawingFactory interface

그리기 관련 객체를 생성하는 팩토리를 나타냅니다.

```csharp
public interface IDrawingFactory : IDisposable
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [CreateInterpolationColor](../../aspose.svg.drawing/idrawingfactory/createinterpolationcolor/)(*Color, float*) | 지정된 색상과 위치를 사용하여 보간 색상을 생성합니다. |
| [CreateLinearGradientBrush](../../aspose.svg.drawing/idrawingfactory/createlineargradientbrush/)(*RectangleF, IInterpolationColor[]*) | 지정된 매개변수를 사용하여 선형 그라디언트 브러시를 생성합니다. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix)() | 새로운 단위 행렬을 생성합니다. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_1)(*[IMatrix](../imatrix/)*) | 지정된 행렬과 동일한 내용을 가진 새 행렬을 생성합니다. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_2)(*float, float, float, float, float, float*) | 지정된 요소를 사용하여 새 행렬을 생성합니다. |
| [CreateSolidBrush](../../aspose.svg.drawing/idrawingfactory/createsolidbrush/)(*Color*) | 지정된 색상을 사용하여 솔리드 브러시를 생성합니다. |
| [CreateTextureBrush](../../aspose.svg.drawing/idrawingfactory/createtexturebrush/)(*byte[]*) | 지정된 매개변수를 사용하여 텍스처 브러시를 생성합니다. |

### 또 보기

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
