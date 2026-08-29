---
title: "SVGBuilderExtensions.AddFeGaussianBlur"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddFeGaussianBlur 메서드. feGaussianBlur 요소 구성을 빌더에 추가합니다. 이 요소는 입력 이미지에 가우시안 블러를 적용합니다."
type: docs
weight: 220
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addfegaussianblur/
---
## AddFeGaussianBlur<TBuilder>(*this TBuilder, Action&lt;SVGFEGaussianBlurElementBuilder&gt;*) {#addfegaussianblur_1}

빌더에 'feGaussianBlur' 요소 구성을 추가합니다. 이 요소는 입력 이미지에 가우시안 블러를 적용합니다.

```csharp
public static TBuilder AddFeGaussianBlur<TBuilder>(this TBuilder builder, 
    Action<SVGFEGaussianBlurElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'feGaussianBlur' 요소에 대한 구성 작업. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGFEGaussianBlurElementBuilder](../../svgfegaussianblurelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeGaussianBlur<TBuilder>(*this TBuilder, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEGaussianBlurElementBuilder&gt;*) {#addfegaussianblur}

SVG 빌더에 'feGaussianBlur' 요소를 추가하여 입력 이미지에 가우시안 블러 효과를 적용합니다.

```csharp
public static TBuilder AddFeGaussianBlur<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, double)> stdDeviation = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEGaussianBlurElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 유창한 API 사용을 가능하게 하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | 'feGaussianBlur' 요소가 추가될 SVG 빌더 인스턴스. |
| stdDeviation | 블러 작업의 표준 편차. double 또는 두 개의 double을 포함하는 ValueTuple일 수 있습니다. 선택적 매개변수. |
| in | 가우시안 블러가 적용될 입력 이미지. 문자열 또는 FilterInput일 수 있습니다. 선택적 매개변수. |
| result | 이 필터 프리미티브에 대한 결과 식별자입니다. 선택 매개변수. |
| x | 필터 프리미티브 하위 영역의 x 좌표입니다. double 또는 LengthType을 포함한 ValueTuple일 수 있습니다. 선택 매개변수. |
| y | 필터 프리미티브 하위 영역의 y 좌표입니다. double 또는 LengthType을 포함한 ValueTuple일 수 있습니다. 선택 매개변수. |
| width | 필터 프리미티브 하위 영역의 너비입니다. double 또는 LengthType을 포함한 ValueTuple일 수 있습니다. 선택 매개변수. |
| height | 필터 프리미티브 하위 영역의 높이입니다. double 또는 LengthType을 포함한 ValueTuple일 수 있습니다. 선택 매개변수. |
| fill | 요소의 채우기 색상, 페인트 또는 페인트 서버 ID입니다. 선택 매개변수. |
| stroke | 요소의 스트로크 색상, 페인트 또는 페인트 서버 ID입니다. 선택 매개변수. |
| id | 필터 프리미티브 요소에 대한 고유 식별자입니다. 선택 매개변수. |
| extend | SVGFEGaussianBlurElementBuilder를 추가로 구성하기 위한 선택적 작업. |

### 반환 값

빌더 인스턴스이며, 메서드 체이닝을 허용합니다.

### 또 보기

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEGaussianBlurElementBuilder](../../svgfegaussianblurelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
