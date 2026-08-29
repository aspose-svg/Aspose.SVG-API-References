---
title: "SVGBuilderExtensions.AddLine"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddLine 메서드. builder에 line 요소 구성을 추가합니다."
type: docs
weight: 350
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addline/
---
## AddLine<TBuilder>(*this TBuilder, Action&lt;SVGLineElementBuilder&gt;*) {#addline_1}

빌더에 'line' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    Action<SVGLineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'line' 요소에 대한 구성 작업입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLine<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGLineElementBuilder&gt;*) {#addline}

SVG 빌더에 지정된 시작점과 끝점, 스타일을 가진 'line' 요소를 추가합니다.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1 = null, OneOf<double, (double, LengthType)> y1 = null, 
    OneOf<double, (double, LengthType)> x2 = null, OneOf<double, (double, LengthType)> y2 = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGLineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 유창한 API 사용을 가능하게 하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | 'line' 요소가 추가될 SVG builder 인스턴스입니다. |
| x1 | 라인 시작점의 x 좌표입니다. double 값이거나 double과 LengthType의 튜플일 수 있습니다. |
| y1 | 라인 시작점의 y 좌표입니다. double 값이거나 double과 LengthType의 튜플일 수 있습니다. |
| x2 | 선의 끝점의 x좌표입니다. double 값이거나 double과 LengthType의 튜플일 수 있습니다. |
| y2 | 선의 끝점의 y좌표입니다. double 값이거나 double과 LengthType의 튜플일 수 있습니다. |
| fill | 선의 채우기 색상 또는 페인트 스타일입니다. Color이거나 Paint 열거형 값 또는 페인트 서버 ID일 수 있습니다. 선택 매개변수. |
| stroke | 선의 스트로크 색상 또는 페인트 스타일입니다. Color이거나 Paint 열거형 값 또는 페인트 서버 ID일 수 있습니다. 선택 매개변수. |
| id | 선 요소에 대한 고유 식별자입니다. 선택 매개변수. |
| extend | 선 요소 빌더를 추가로 구성하기 위한 선택적 작업입니다. |

### 반환 값

빌더 인스턴스이며, 메서드 체이닝을 허용합니다.

### 또 보기

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
