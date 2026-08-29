---
title: "SVGBuilderExtensions.AddRadialGradient"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddRadialGradient 메서드. radialGradient 요소 구성을 빌더에 추가합니다."
type: docs
weight: 440
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addradialgradient/
---
## AddRadialGradient<TBuilder>(*this TBuilder, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient_1}

빌더에 'radialGradient' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    Action<SVGRadialGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | ‘radialGradient’ 요소에 대한 구성 작업입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRadialGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient}

SVG 빌더에 'radialGradient' 요소를 추가하고, 중심, 반경, 초점 위치 및 기타 그라디언트 속성을 지정합니다.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<double, (double, LengthType)> fx = null, 
    OneOf<double, (double, LengthType)> fy = null, CoordinateUnits? gradientUnits = default, 
    SpreadMethod? spreadMethod = default, string href = null, string id = null, 
    Action<SVGRadialGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 유창한 API 사용을 가능하게 하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | ‘radialGradient’ 요소가 추가될 SVG 빌더 인스턴스입니다. |
| cx | 그라디언트 중심의 x 좌표입니다. double 또는 LengthType이 포함된 ValueTuple일 수 있습니다. 선택 매개변수입니다. |
| cy | 그라디언트 중심의 y 좌표입니다. double 또는 LengthType이 포함된 ValueTuple일 수 있습니다. 선택 매개변수입니다. |
| r | 그라디언트의 반경입니다. double 또는 LengthType이 포함된 ValueTuple일 수 있습니다. 선택 매개변수입니다. |
| fx | 그라디언트 초점의 x 좌표입니다. double 또는 LengthType이 포함된 ValueTuple일 수 있습니다. 선택 매개변수입니다. |
| fy | 그라디언트 초점의 y 좌표입니다. double 또는 LengthType이 포함된 ValueTuple일 수 있습니다. 선택 매개변수입니다. |
| gradientUnits | 그라디언트에 대한 좌표 시스템을 지정합니다. 선택 매개변수입니다. |
| spreadMethod | 그라디언트가 시작점과 끝점을 넘어 어떻게 퍼지는지를 정의합니다. 선택 매개변수입니다. |
| href | 해당되는 경우 다른 그라디언트에 대한 참조입니다. 선택 매개변수입니다. |
| id | 그라디언트 요소의 고유 식별자입니다. 선택 매개변수입니다. |
| extend | radial gradient 요소 빌더를 추가로 구성하기 위한 선택적 작업입니다. |

### 반환 값

빌더 인스턴스이며, 메서드 체이닝을 허용합니다.

### 또 보기

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
