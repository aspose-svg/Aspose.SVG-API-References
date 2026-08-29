---
title: "SVGBuilderExtensions.AddFeOffset"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddFeOffset 메서드. builder에 feOffset 요소 구성을 추가합니다. 이 요소는 지정된 벡터만큼 입력 이미지를 오프셋합니다."
type: docs
weight: 260
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addfeoffset/
---
## AddFeOffset<TBuilder>(*this TBuilder, Action&lt;SVGFEOffsetElementBuilder&gt;*) {#addfeoffset}

빌더에 'feOffset' 요소 구성을 추가합니다. 이 요소는 지정된 벡터만큼 입력 이미지를 오프셋합니다.

```csharp
public static TBuilder AddFeOffset<TBuilder>(this TBuilder builder, 
    Action<SVGFEOffsetElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'feOffset' 요소에 대한 구성 작업. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGFEOffsetElementBuilder](../../svgfeoffsetelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeOffset<TBuilder>(*this TBuilder, double?, double?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEOffsetElementBuilder&gt;*) {#addfeoffset_1}

SVG 빌더에 'feOffset' 요소를 추가하여 지정된 벡터만큼 입력 이미지를 이동시켜 오프셋 효과를 만듭니다.

```csharp
public static TBuilder AddFeOffset<TBuilder>(this TBuilder builder, double? dx = null, 
    double? dy = null, OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEOffsetElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 유창한 API 사용을 가능하게 하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | 'feOffset' 요소가 추가될 SVG builder 인스턴스. |
| dx | 수평 오프셋 거리. 선택 매개변수. |
| dy | 수직 오프셋 거리. 선택 매개변수. |
| in | 오프셋이 적용될 입력 이미지. 문자열 또는 FilterInput일 수 있습니다. 선택 매개변수. |
| result | 이 필터 프리미티브에 대한 결과 식별자입니다. 선택 매개변수. |
| x | 필터 프리미티브 하위 영역의 x 좌표입니다. double 또는 LengthType을 포함한 ValueTuple일 수 있습니다. 선택 매개변수. |
| y | 필터 프리미티브 하위 영역의 y 좌표입니다. double 또는 LengthType을 포함한 ValueTuple일 수 있습니다. 선택 매개변수. |
| width | 필터 프리미티브 하위 영역의 너비입니다. double 또는 LengthType을 포함한 ValueTuple일 수 있습니다. 선택 매개변수. |
| height | 필터 프리미티브 하위 영역의 높이입니다. double 또는 LengthType을 포함한 ValueTuple일 수 있습니다. 선택 매개변수. |
| fill | 요소의 채우기 색상, 페인트 또는 페인트 서버 ID입니다. 선택 매개변수. |
| stroke | 요소의 스트로크 색상, 페인트 또는 페인트 서버 ID입니다. 선택 매개변수. |
| id | 필터 프리미티브 요소에 대한 고유 식별자입니다. 선택 매개변수. |
| extend | SVGFEOffsetElementBuilder를 추가로 구성하기 위한 선택 작업. |

### 반환 값

빌더 인스턴스이며, 메서드 체이닝을 허용합니다.

### 또 보기

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEOffsetElementBuilder](../../svgfeoffsetelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
