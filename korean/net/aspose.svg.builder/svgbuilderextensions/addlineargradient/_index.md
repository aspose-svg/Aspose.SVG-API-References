---
title: "SVGBuilderExtensions.AddLinearGradient"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddLinearGradient 메서드. 빌더에 linearGradient 요소 구성을 추가합니다."
type: docs
weight: 360
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addlineargradient/
---
## AddLinearGradient<TBuilder>(*this TBuilder, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient_1}

빌더에 'linearGradient' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    Action<SVGLinearGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'linearGradient' 요소에 대한 구성 작업입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLinearGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient}

SVG 빌더에 'linearGradient' 요소를 추가하여 시작 및 끝 위치와 기타 그라디언트 속성을 지정합니다.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1, OneOf<double, (double, LengthType)> y1, 
    OneOf<double, (double, LengthType)> x2, OneOf<double, (double, LengthType)> y2, 
    CoordinateUnits? gradientUnits, SpreadMethod? spreadMethod, string href = null, 
    string id = null, Action<SVGLinearGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 유창한 API 사용을 가능하게 하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | 'linearGradient' 요소가 추가될 SVG 빌더 인스턴스입니다. |
| x1 | 그라디언트의 시작 x 좌표입니다. double이거나 LengthType이 포함된 ValueTuple일 수 있습니다. |
| y1 | 그라디언트의 시작 y 좌표입니다. double이거나 LengthType이 포함된 ValueTuple일 수 있습니다. |
| x2 | 그라디언트의 끝 x좌표입니다. double 또는 LengthType이 있는 ValueTuple일 수 있습니다. |
| y2 | 그라디언트의 끝 y좌표입니다. double 또는 LengthType이 있는 ValueTuple일 수 있습니다. |
| gradientUnits | 그라디언트에 대한 좌표 시스템을 지정합니다. 선택 매개변수입니다. |
| spreadMethod | 그라디언트가 시작점과 끝점을 넘어 어떻게 퍼지는지를 정의합니다. 선택 매개변수입니다. |
| href | 해당되는 경우 다른 그라디언트에 대한 참조입니다. 선택 매개변수입니다. |
| id | 그라디언트 요소의 고유 식별자입니다. 선택 매개변수입니다. |
| extend | 선형 그라디언트 요소 빌더를 추가로 구성하기 위한 선택적 액션입니다. |

### 반환 값

빌더 인스턴스이며, 메서드 체이닝을 허용합니다.

### 또 보기

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
