---
title: "SVGBuilderExtensions.AddPolyline"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddPolyline 메서드. 빌더에 폴리라인 요소 구성을 추가합니다."
type: docs
weight: 430
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addpolyline/
---
## AddPolyline<TBuilder>(*this TBuilder, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline_1}

빌더에 'polyline' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, 
    Action<SVGPolylineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'polyline' 요소에 대한 구성 작업. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolyline<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline}

SVG 빌더에 'polyline' 요소를 추가하고, 정점과 스타일을 지정합니다.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolylineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 유창한 API 사용을 가능하게 하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | 'polyline' 요소가 추가될 SVG 빌더 인스턴스. |
| points | 폴리라인의 점들을 나타내는 double 배열 (x와 y 좌표가 교대로). |
| fill | 폴리라인의 채우기 색상 또는 페인트 스타일. Color, Paint 열거형 값 또는 페인트 서버 ID일 수 있습니다. 선택 매개변수. |
| stroke | 폴리라인의 스트로크 색상 또는 페인트 스타일. Color, Paint 열거형 값 또는 페인트 서버 ID일 수 있습니다. 선택 매개변수. |
| id | 폴리라인 요소의 고유 식별자. 선택 매개변수. |
| extend | 폴리라인 요소 빌더를 추가로 구성하기 위한 선택적 작업. |

### 반환 값

빌더 인스턴스이며, 메서드 체이닝을 허용합니다.

### 또 보기

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
