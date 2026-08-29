---
title: "SVGBuilderExtensions.GradientUnits"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions GradientUnits 메서드. 그라디언트 요소의 gradientUnits 속성을 설정합니다"
type: docs
weight: 990
url: /ko/net/aspose.svg.builder/svgbuilderextensions/gradientunits/
---
## SVGBuilderExtensions.GradientUnits<TBuilder> method

그라디언트 요소에 대한 'gradientUnits' 속성을 설정합니다.

```csharp
public static TBuilder GradientUnits<TBuilder>(this TBuilder builder, CoordinateUnits units)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 속성이 적용되는 SVG 요소 빌더입니다. |
| 단위 | 그라디언트의 좌표 단위 (userSpaceOnUse 또는 objectBoundingBox)입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [CoordinateUnits](../../coordinateunits/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
