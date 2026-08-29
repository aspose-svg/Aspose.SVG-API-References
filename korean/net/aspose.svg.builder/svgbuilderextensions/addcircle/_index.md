---
title: "SVGBuilderExtensions.AddCircle"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddCircle 메서드. 빌더에 circle 요소 구성을 추가합니다"
type: docs
weight: 70
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addcircle/
---
## AddCircle<TBuilder>(*this TBuilder, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle_1}

빌더에 'circle' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    Action<SVGCircleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'circle' 요소에 대한 구성 작업입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddCircle<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle}

지정된 중심, 반경 및 스타일을 가진 'circle' 요소를 SVG 빌더에 추가합니다.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGCircleElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 유창한 API 사용을 가능하게 하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | 'circle' 요소가 추가될 SVG 빌더 인스턴스입니다. |
| cx | 원 중심의 x 좌표입니다. double 값이거나 double과 LengthType의 튜플일 수 있습니다. |
| cy | 원 중심의 y 좌표입니다. double 값이거나 double과 LengthType의 튜플일 수 있습니다. |
| r | 원의 반지름입니다. double 값이거나 double과 LengthType의 튜플일 수 있습니다. |
| fill | 원의 채우기 색상 또는 페인트 스타일입니다. Color이거나 Paint 열거형 값 또는 페인트 서버 ID일 수 있습니다. 선택적 매개변수입니다. |
| stroke | 원의 외곽선 색상 또는 페인트 스타일입니다. Color이거나 Paint 열거형 값 또는 페인트 서버 ID일 수 있습니다. 선택적 매개변수입니다. |
| id | circle 요소의 고유 식별자입니다. 선택적 매개변수입니다. |
| extend | 원 요소 빌더를 추가로 구성하기 위한 선택적 작업입니다. |

### 반환 값

빌더 인스턴스이며, 메서드 체이닝을 허용합니다.

### 또 보기

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
