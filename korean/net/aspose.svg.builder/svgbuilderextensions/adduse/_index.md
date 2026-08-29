---
title: "SVGBuilderExtensions.AddUse"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddUse 메서드. 빌더에 use 요소 구성을 추가합니다."
type: docs
weight: 550
url: /ko/net/aspose.svg.builder/svgbuilderextensions/adduse/
---
## AddUse<TBuilder>(*this TBuilder, Action&lt;SVGUseElementBuilder&gt;*) {#adduse}

빌더에 'use' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddUse<TBuilder>(this TBuilder builder, 
    Action<SVGUseElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'use' 요소에 대한 구성 작업. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGUseElementBuilder](../../svguseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddUse<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGUseElementBuilder&gt;*) {#adduse_1}

SVG 빌더에 'use' 요소를 추가하여 SVG 내 다른 곳에 정의된 기존 요소를 재사용할 수 있게 합니다.

```csharp
public static TBuilder AddUse<TBuilder>(this TBuilder builder, string href = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGUseElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 유창한 API 사용을 가능하게 하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | 'use' 요소가 추가될 SVG 빌더 인스턴스. |
| href | 재사용될 기존 요소에 대한 참조. 선택 매개변수. |
| x | 재사용된 요소가 배치되는 x 좌표. double 또는 LengthType이 포함된 ValueTuple일 수 있습니다. 선택 매개변수. |
| y | 재사용된 요소가 배치되는 y 좌표. double 또는 LengthType이 포함된 ValueTuple일 수 있습니다. 선택 매개변수. |
| width | 재사용된 요소의 너비. double 또는 LengthType이 포함된 ValueTuple일 수 있습니다. 선택 매개변수. |
| height | 재사용된 요소의 높이. double 또는 LengthType이 포함된 ValueTuple일 수 있습니다. 선택 매개변수. |
| fill | 요소의 채우기 색상, 페인트 또는 페인트 서버 ID입니다. 선택 매개변수. |
| stroke | 요소의 스트로크 색상, 페인트 또는 페인트 서버 ID입니다. 선택 매개변수. |
| id | 요소에 대한 고유 식별자. 선택 매개변수. |
| extend | SVGUseElementBuilder를 추가로 구성하기 위한 선택적 작업. |

### 반환 값

빌더 인스턴스이며, 메서드 체이닝을 허용합니다.

### 또 보기

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGUseElementBuilder](../../svguseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
