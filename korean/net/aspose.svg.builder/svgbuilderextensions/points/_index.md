---
title: "SVGBuilderExtensions.Points"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Points 메서드. double 배열을 사용하여 SVG 요소의 points 속성을 설정합니다."
type: docs
weight: 1910
url: /ko/net/aspose.svg.builder/svgbuilderextensions/points/
---
## Points<TBuilder>(*this TBuilder, params double[]*) {#points}

배열의 double 값을 사용하여 SVG 요소의 'points' 속성을 설정합니다.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params double[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| points | 점들을 나타내는 double 배열 (짝수 개여야 함). |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 점의 개수가 홀수인 경우 예외가 발생합니다. |

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Points<TBuilder>(*this TBuilder, params PointF[]*) {#points_1}

PointF 객체 배열을 사용하여 SVG 요소의 'points' 속성을 설정합니다.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params PointF[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| points | 점을 나타내는 PointF 객체 배열. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
