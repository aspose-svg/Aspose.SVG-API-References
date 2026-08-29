---
title: "SVGBuilderExtensions.AddText"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddText 메서드. 빌더에 텍스트 요소 구성을 추가합니다."
type: docs
weight: 530
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addtext/
---
## AddText<TBuilder>(*this TBuilder, Action&lt;SVGTextElementBuilder&gt;*) {#addtext}

빌더에 'text' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, 
    Action<SVGTextElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'text' 요소에 대한 구성 동작입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddText<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, FontStyle?, string, FontWeight?, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGTextElementBuilder&gt;*) {#addtext_1}

SVG 빌더에 지정된 내용과 속성을 가진 'text' 요소를 추가합니다.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, string content, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> fontSize = null, FontStyle? fontStyle = default, 
    string fontFamily = null, FontWeight? fontWeight = default, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGTextElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 체이닝을 허용하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | 'text' 요소가 추가될 빌더 인스턴스입니다. |
| 내용 | 'text' 요소 내에 표시될 텍스트 내용입니다. |
| x | 텍스트 요소의 x 좌표입니다. double 값이나 double과 LengthType의 튜플일 수 있습니다. |
| y | 텍스트 요소의 y 좌표입니다. double 값이나 double과 LengthType의 튜플일 수 있습니다. |
| fontSize | 텍스트의 글꼴 크기입니다. double 값이나 double과 LengthType의 튜플일 수 있습니다. |
| fontStyle | 텍스트의 글꼴 스타일입니다 (예: normal, italic, oblique). |
| fontFamily | 텍스트의 글꼴 패밀리입니다 (예: Arial, Verdana). |
| fontWeight | 글꼴의 두께(무게)입니다 (예: normal, bold). |
| fill | 텍스트의 채우기 색상 또는 페인트 스타일입니다. Color, Paint 열거형 값 또는 페인트 서버 ID일 수 있습니다. |
| stroke | 텍스트의 스트로크 색상 또는 페인트 스타일입니다. Color, Paint 열거형 값 또는 페인트 서버 ID일 수 있습니다. |
| id | 텍스트 요소의 고유 식별자입니다. |
| extend | 텍스트 요소 빌더를 추가로 구성하기 위한 선택적 액션입니다. |

### 반환 값

추가 작업이나 구성을 체이닝하기 위한 빌더 인스턴스입니다.

### 또 보기

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [FontStyle](../../fontstyle/)
* enum [FontWeight](../../fontweight/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
