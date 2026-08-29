---
title: "SVGBuilderExtensions.AddPath"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddPath 메서드. 빌더에 경로 요소 구성을 추가합니다."
type: docs
weight: 400
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addpath/
---
## AddPath<TBuilder>(*this TBuilder, Action&lt;SVGPathElementBuilder&gt;*) {#addpath_2}

빌더에 'path' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, 
    Action<SVGPathElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'path' 요소에 대한 구성 액션입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPath<TBuilder>(*this TBuilder, OneOf&lt;string, Action&lt;PathBuilder&gt;&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPathElementBuilder&gt;*) {#addpath}

SVG 빌더에 'path' 요소를 추가하여 경로 데이터와 스타일을 지정합니다.

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, 
    OneOf<string, Action<PathBuilder>> d, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGPathElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 유창한 API 사용을 가능하게 하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | 'path' 요소가 추가될 SVG 빌더 인스턴스입니다. |
| d | 경로 데이터를 나타내는 문자열이거나 PathBuilder를 구성하는 액션이 될 수 있는 OneOf 타입입니다. |
| fill | 경로의 채우기 색상 또는 페인트 스타일입니다. Color 또는 Paint 열거형 값 또는 페인트 서버 ID일 수 있습니다. 선택적 매개변수입니다. |
| stroke | 경로의 스트로크 색상 또는 페인트 스타일입니다. Color 또는 Paint 열거형 값 또는 페인트 서버 ID일 수 있습니다. 선택적 매개변수입니다. |
| id | 경로 요소의 고유 식별자입니다. 선택적 매개변수입니다. |
| extend | 경로 요소 빌더를 추가로 구성하기 위한 선택적 액션입니다. |

### 반환 값

빌더 인스턴스이며, 메서드 체이닝을 허용합니다.

### 또 보기

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* class [PathBuilder](../../pathbuilder/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPath<TBuilder>(*this TBuilder, Action&lt;PathBuilder&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPathElementBuilder&gt;*) {#addpath_1}

PathBuilder를 직접 구성하는 액션을 받는 AddPath의 오버로드입니다.

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, Action<PathBuilder> d, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPathElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 유창한 API 사용을 가능하게 하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | 'path' 요소가 추가될 SVG 빌더 인스턴스입니다. |
| d | 경로 데이터를 정의하기 위해 PathBuilder를 구성하는 액션입니다. |
| fill | 경로의 채우기 색상 또는 페인트 스타일입니다. Color 또는 Paint 열거형 값 또는 페인트 서버 ID일 수 있습니다. 선택적 매개변수입니다. |
| stroke | 경로의 스트로크 색상 또는 페인트 스타일입니다. Color 또는 Paint 열거형 값 또는 페인트 서버 ID일 수 있습니다. 선택적 매개변수입니다. |
| id | 경로 요소의 고유 식별자입니다. 선택적 매개변수입니다. |
| extend | 경로 요소 빌더를 추가로 구성하기 위한 선택적 액션입니다. |

### 반환 값

빌더 인스턴스이며, 메서드 체이닝을 허용합니다.

### 또 보기

* class [PathBuilder](../../pathbuilder/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
