---
title: "SVGBuilderExtensions.AddAnimateTransform"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddAnimateTransform 메서드. 빌더에 animateTransform 요소 구성을 추가합니다."
type: docs
weight: 50
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addanimatetransform/
---
## SVGBuilderExtensions.AddAnimateTransform<TBuilder> method

빌더에 'animateTransform' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddAnimateTransform<TBuilder>(this TBuilder builder, 
    Action<SVGAnimateTransformElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'animateTransform' 요소에 대한 구성 작업입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGAnimateTransformElementBuilder](../../svganimatetransformelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationElementBuilder](../../ianimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
