---
title: "SVGBuilderExtensions.AddPattern"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddPattern 메서드. 빌더에 패턴 요소 구성을 추가합니다."
type: docs
weight: 410
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addpattern/
---
## AddPattern<TBuilder>(*this TBuilder, Action&lt;SVGPatternElementBuilder&gt;*) {#addpattern}

빌더에 'pattern' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddPattern<TBuilder>(this TBuilder builder, 
    Action<SVGPatternElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'pattern' 요소에 대한 구성 작업입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGPatternElementBuilder](../../svgpatternelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPattern<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, string, string, Action&lt;SVGPatternElementBuilder&gt;*) {#addpattern_1}

SVG 빌더에 'pattern' 요소를 추가하고, 패턴 내용의 좌표계와 단위를 지정합니다.

```csharp
public static TBuilder AddPattern<TBuilder>(this TBuilder builder, CoordinateUnits? patternUnits, 
    CoordinateUnits? patternContentUnits, string href = null, string id = null, 
    Action<SVGPatternElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 유창한 API 사용을 가능하게 하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | 'pattern' 요소가 추가될 SVG 빌더 인스턴스입니다. |
| patternUnits | 패턴에 대한 좌표 시스템을 지정합니다. 선택 매개변수입니다. |
| patternContentUnits | 패턴 내 콘텐츠에 대한 좌표 시스템을 지정합니다. 선택 매개변수. |
| href | 해당되는 경우 다른 패턴에 대한 참조입니다. 선택 매개변수. |
| id | 패턴 요소에 대한 고유 식별자입니다. 선택 매개변수. |
| extend | 패턴 요소 빌더를 추가로 구성하기 위한 선택적 동작입니다. |

### 반환 값

빌더 인스턴스이며, 메서드 체이닝을 허용합니다.

### 또 보기

* enum [CoordinateUnits](../../coordinateunits/)
* class [SVGPatternElementBuilder](../../svgpatternelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
