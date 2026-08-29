---
title: "SVGBuilderExtensions.AddFeComposite"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddFeComposite 메서드. builder에 feComposite 요소 구성을 추가합니다. 이 요소는 두 입력 그래픽을 비트 단위로 결합합니다."
type: docs
weight: 160
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addfecomposite/
---
## AddFeComposite<TBuilder>(*this TBuilder, Action&lt;SVGFECompositeElementBuilder&gt;*) {#addfecomposite}

빌더에 'feComposite' 요소 구성을 추가합니다. 이 요소는 두 입력 그래픽을 비트 단위로 결합합니다.

```csharp
public static TBuilder AddFeComposite<TBuilder>(this TBuilder builder, 
    Action<SVGFECompositeElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'feComposite' 요소에 대한 구성 동작입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGFECompositeElementBuilder](../../svgfecompositeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeComposite<TBuilder>(*this TBuilder, CompositeOperator?, double?, double?, double?, double?, OneOf&lt;string, FilterInput&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFECompositeElementBuilder&gt;*) {#addfecomposite_1}

SVG 빌더에 'feComposite' 요소를 추가하고, 합성 연산 및 입력 이미지를 결합하기 위한 다양한 기타 속성을 지정합니다.

```csharp
public static TBuilder AddFeComposite<TBuilder>(this TBuilder builder, 
    CompositeOperator? compositeOperator, double? k1, double? k2, double? k3, double? k4, 
    OneOf<string, FilterInput> @in = null, OneOf<string, FilterInput> in2 = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFECompositeElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 유창한 API 사용을 가능하게 하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | 'feComposite' 요소가 추가될 SVG builder 인스턴스입니다. |
| compositeOperator | 사용할 composite operator입니다. 선택 매개변수. |
| k1 | composite 연산에 대한 첫 번째 숫자 값입니다. 선택 매개변수. |
| k2 | composite 연산에 대한 두 번째 숫자 값입니다. 선택 매개변수. |
| k3 | composite 연산에 대한 세 번째 숫자 값입니다. 선택 매개변수. |
| k4 | composite 연산에 대한 네 번째 숫자 값입니다. 선택 매개변수. |
| in | composite 효과에 대한 첫 번째 입력입니다. 문자열이나 FilterInput일 수 있습니다. 선택 매개변수. |
| in2 | 합성 효과에 대한 두 번째 입력입니다. 문자열이나 FilterInput일 수 있습니다. 선택적 매개변수입니다. |
| result | 이 필터 프리미티브에 대한 결과 식별자입니다. 선택 매개변수. |
| x | 필터 프리미티브 하위 영역의 x 좌표입니다. double 또는 LengthType을 포함한 ValueTuple일 수 있습니다. 선택 매개변수. |
| y | 필터 프리미티브 하위 영역의 y 좌표입니다. double 또는 LengthType을 포함한 ValueTuple일 수 있습니다. 선택 매개변수. |
| width | 필터 프리미티브 하위 영역의 너비입니다. double 또는 LengthType을 포함한 ValueTuple일 수 있습니다. 선택 매개변수. |
| height | 필터 프리미티브 하위 영역의 높이입니다. double 또는 LengthType을 포함한 ValueTuple일 수 있습니다. 선택 매개변수. |
| fill | 요소의 채우기 색상, 페인트 또는 페인트 서버 ID입니다. 선택 매개변수. |
| stroke | 요소의 스트로크 색상, 페인트 또는 페인트 서버 ID입니다. 선택 매개변수. |
| id | 필터 프리미티브 요소에 대한 고유 식별자입니다. 선택 매개변수. |
| extend | SVGFECompositeElementBuilder를 추가로 구성하기 위한 선택적 작업입니다. |

### 반환 값

빌더 인스턴스이며, 메서드 체이닝을 허용합니다.

### 또 보기

* enum [CompositeOperator](../../compositeoperator/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFECompositeElementBuilder](../../svgfecompositeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
