---
title: "SVGBuilderExtensions.AddFilter"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddFilter 메서드. 필터 요소 구성을 빌더에 추가합니다."
type: docs
weight: 300
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addfilter/
---
## AddFilter<TBuilder>(*this TBuilder, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter}

빌더에 'filter' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    Action<SVGFilterElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'filter' 요소에 대한 구성 작업입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFilter<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter_1}

SVG 빌더에 'filter' 요소를 추가하여 SVG 요소에 적용할 수 있는 필터 효과를 정의합니다.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    CoordinateUnits? filterUnits = default, CoordinateUnits? primitiveUnits = default, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFilterElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 유창한 API 사용을 가능하게 하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | 'filter' 요소가 추가될 SVG 빌더 인스턴스입니다. |
| filterUnits | 필터의 x, y, width 및 height 속성에 대한 좌표 시스템을 지정합니다. 선택적 매개변수입니다. |
| primitiveUnits | 필터의 자식 요소 속성에 대한 좌표 시스템을 지정합니다. 선택적 매개변수입니다. |
| x | 필터 영역의 x 좌표입니다. double 또는 LengthType이 포함된 ValueTuple일 수 있습니다. 선택적 매개변수입니다. |
| y | 필터 영역의 y 좌표입니다. double 또는 LengthType이 포함된 ValueTuple일 수 있습니다. 선택적 매개변수입니다. |
| width | 필터 영역의 너비입니다. double 또는 LengthType이 포함된 ValueTuple일 수 있습니다. 선택적 매개변수입니다. |
| height | 필터 영역의 높이입니다. double 또는 LengthType이 포함된 ValueTuple일 수 있습니다. 선택적 매개변수입니다. |
| fill | 필터 요소의 채우기 색상 또는 페인트입니다. 선택적 매개변수입니다. |
| stroke | 필터 요소의 스트로크 색상 또는 페인트입니다. 선택적 매개변수입니다. |
| id | 필터 요소의 고유 식별자입니다. 선택적 매개변수입니다. |
| extend | SVGFilterElementBuilder를 추가로 구성하기 위한 선택적 작업입니다. |

### 반환 값

빌더 인스턴스이며, 메서드 체이닝을 허용합니다.

### 또 보기

* enum [CoordinateUnits](../../coordinateunits/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
