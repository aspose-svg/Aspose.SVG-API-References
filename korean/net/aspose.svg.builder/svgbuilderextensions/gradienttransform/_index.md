---
title: "SVGBuilderExtensions.GradientTransform"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions GradientTransform 메서드. 그라디언트 요소에 대한 gradientTransform 속성을 설정합니다."
type: docs
weight: 980
url: /ko/net/aspose.svg.builder/svgbuilderextensions/gradienttransform/
---
## SVGBuilderExtensions.GradientTransform<TBuilder> method

그라디언트 요소에 대한 'gradientTransform' 속성을 설정합니다.

```csharp
public static TBuilder GradientTransform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 속성이 적용되는 SVG 요소 빌더입니다. |
| 구성 | SVG 변환 빌더를 구성하는 함수입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
