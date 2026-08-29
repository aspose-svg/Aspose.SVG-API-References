---
title: "SVGGeometryElement.Combine"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGGeometryElement Combine 메서드. 이 기하학을 다른 SVG 기하학과 불리언 연산을 사용하여 결합하고 결과를 포함하는 새로운 path 요소를 반환합니다."
type: docs
weight: 20
url: /ko/net/aspose.svg/svggeometryelement/combine/
---
## SVGGeometryElement.Combine method

이 기하학을 다른 SVG 기하학과 불리언 연산을 사용하여 결합하고, 결과를 포함하는 새로운 `<path>` 요소를 반환합니다.

```csharp
public SVGPathElement Combine(SVGGeometryElement geometryElement, BooleanPathOp op)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| geometryElement | SVGGeometryElement | 결합할 다른 기하학. 동일한 문서에 있어야 합니다. |
| op | BooleanPathOp | 적용할 부울 연산자: 합집합 (A UNION B), 차집합 (A - B), 교집합 (A INTERSECT B), 혹은 배제 (XOR). |

### 반환 값

새로운 [`SVGPathElement`](../../svgpathelement/)으로, `d` 속성이 결과를 루트 `<svg>` 사용자 공간(CSS px)으로 인코딩합니다. 이 요소는 DOM에 추가되지 않습니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *geometryElement*가 null인 경우 발생합니다. |
| InvalidOperationException | 이 요소에 소유 문서가 없을 경우 발생합니다. |
| NotSupportedException | 부울 경로 연산을 사용할 수 없을 때 발생합니다; 이 기능은 SkiaSharp 백엔드가 필요합니다(Aspose.SVG.Drawing.SkiaSharp 패키지를 설치하십시오). |

### 또 보기

* class [SVGPathElement](../../svgpathelement/)
* enum [BooleanPathOp](../../../aspose.svg.rendering/booleanpathop/)
* class [SVGGeometryElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
