---
title: "SVGBuilderExtensions.KeySplines"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions KeySplines 메서드. 애니메이션 속도를 제어하는 ​​키 포인트를 지정하는 keySplines 속성을 설정합니다."
type: docs
weight: 1060
url: /ko/net/aspose.svg.builder/svgbuilderextensions/keysplines/
---
## SVGBuilderExtensions.KeySplines<TBuilder> method

'keySplines' 속성을 설정하고, 애니메이션 속도 조절을 위한 제어점을 지정합니다.

```csharp
public static TBuilder KeySplines<TBuilder>(this TBuilder builder, 
    Action<AnimationSplineBuilder> buildSplines)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| buildSplines | 스플라인 구성을 구축하는 동작입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [AnimationSplineBuilder](../../animationsplinebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
