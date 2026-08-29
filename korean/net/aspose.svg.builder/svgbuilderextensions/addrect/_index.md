---
title: "SVGBuilderExtensions.AddRect"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddRect 메서드. rect 요소 구성을 빌더에 추가합니다"
type: docs
weight: 450
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addrect/
---
## AddRect<TBuilder>(*this TBuilder, Action&lt;SVGRectElementBuilder&gt;*) {#addrect_1}

빌더에 'rect' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    Action<SVGRectElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'rect' 요소에 대한 구성 작업입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRect<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGRectElementBuilder&gt;*) {#addrect}

SVG 빌더에 지정된 크기와 스타일을 가진 'rect' (사각형) 요소를 추가합니다.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGRectElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 유창한 API 사용을 가능하게 하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | 'rect' 요소가 추가될 SVG 빌더 인스턴스입니다. |
| x | 사각형 시작점의 x 좌표입니다. double 값이거나 double과 LengthType의 튜플일 수 있습니다. |
| y | 사각형 시작점의 y 좌표입니다. double 값이거나 double과 LengthType의 튜플일 수 있습니다. |
| width | 사각형의 너비입니다. double 값이거나 double과 LengthType의 튜플일 수 있습니다. |
| height | 사각형의 높이입니다. double 값이거나 double과 LengthType의 튜플일 수 있습니다. |
| fill | 사각형의 채우기 색상 또는 페인트 스타일입니다. Color이거나 Paint 열거형 값 또는 페인트 서버 ID일 수 있습니다. 선택 매개변수입니다. |
| stroke | 사각형 외곽선의 스트로크 색상 또는 페인트 스타일입니다. Color이거나 Paint 열거형 값 또는 페인트 서버 ID일 수 있습니다. 선택 매개변수입니다. |
| id | 사각형 요소의 고유 식별자입니다. 선택 매개변수입니다. |
| extend | 사각형 요소 빌더를 추가로 구성하기 위한 선택적 작업입니다. |

### 반환 값

빌더 인스턴스이며, 메서드 체이닝을 허용합니다.

### 또 보기

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
