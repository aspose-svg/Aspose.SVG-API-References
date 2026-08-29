---
title: "SVGBuilderExtensions.AddEllipse"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddEllipse 메서드. 빌더에 타원 요소 구성을 추가합니다."
type: docs
weight: 120
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addellipse/
---
## AddEllipse<TBuilder>(*this TBuilder, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse_1}

빌더에 'ellipse' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    Action<SVGEllipseElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'ellipse' 요소에 대한 구성 액션. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddEllipse<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse}

SVG 빌더에 'ellipse' 요소를 추가하고, 중심, 반지름 및 스타일을 지정합니다.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> rx = null, OneOf<double, (double, LengthType)> ry = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGEllipseElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 유창한 API 사용을 가능하게 하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | 'ellipse' 요소가 추가될 SVG 빌더 인스턴스. |
| cx | 타원의 중심의 x좌표입니다. double 값이거나 double과 LengthType의 튜플일 수 있습니다. |
| cy | 타원의 중심의 y좌표입니다. double 값이거나 double과 LengthType의 튜플일 수 있습니다. |
| rx | 타원의 x반경입니다. double 값이거나 double과 LengthType의 튜플일 수 있습니다. |
| ry | 타원의 y반경입니다. double 값이거나 double과 LengthType의 튜플일 수 있습니다. |
| fill | 타원의 채우기 색상 또는 페인트 스타일입니다. Color이거나 Paint 열거형 값 또는 페인트 서버 ID일 수 있습니다. 선택 매개변수. |
| stroke | 타원의 스트로크 색상 또는 페인트 스타일입니다. Color이거나 Paint 열거형 값 또는 페인트 서버 ID일 수 있습니다. 선택 매개변수. |
| id | 타원 요소의 고유 식별자입니다. 선택 매개변수. |
| extend | 타원 요소 빌더를 추가로 구성하기 위한 선택적 동작입니다. |

### 반환 값

빌더 인스턴스이며, 메서드 체이닝을 허용합니다.

### 또 보기

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
