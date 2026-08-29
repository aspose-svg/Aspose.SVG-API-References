---
title: "SVGBuilderExtensions.AddStop"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddStop 메서드. 그라디언트 스톱을 정의하기 위해 빌더에 stop 요소 구성을 추가합니다"
type: docs
weight: 480
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addstop/
---
## AddStop<TBuilder>(*this TBuilder, Action&lt;SVGStopElementBuilder&gt;*) {#addstop}

그라디언트 정지를 정의하기 위해 빌더에 'stop' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddStop<TBuilder>(this TBuilder builder, 
    Action<SVGStopElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'stop' 요소에 대한 구성 작업. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGStopElementBuilder](../../svgstopelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddStop<TBuilder>(*this TBuilder, Color?, double?, OneOf&lt;double, (double, StopUnitType)&gt;, string, Action&lt;SVGStopElementBuilder&gt;*) {#addstop_1}

SVG 빌더의 그라디언트에 'stop' 요소를 추가하고, 특정 오프셋에서 색상과 불투명도를 지정합니다.

```csharp
public static TBuilder AddStop<TBuilder>(this TBuilder builder, Color? stopColor = default, 
    double? stopOpacity = null, OneOf<double, (double, StopUnitType)> offset = null, 
    string id = null, Action<SVGStopElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 유창한 API 사용을 가능하게 하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | 'stop' 요소가 추가될 SVG 빌더 인스턴스. |
| stopColor | 스톱에서의 색상. 선택 매개변수. |
| stopOpacity | 스톱에서의 불투명도. 선택 매개변수. |
| offset | 그라디언트 내에서 스톱의 오프셋. double 또는 StopUnitType이 포함된 ValueTuple일 수 있습니다. 선택 매개변수. |
| id | 스톱 요소의 고유 식별자. 선택 매개변수. |
| extend | 스톱 요소 빌더를 추가로 구성하기 위한 선택적 작업. |

### 반환 값

빌더 인스턴스이며, 메서드 체이닝을 허용합니다.

### 또 보기

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [StopUnitType](../../stopunittype/)
* class [SVGStopElementBuilder](../../svgstopelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
