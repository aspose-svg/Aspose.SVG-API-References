---
title: "SVGBuilderExtensions.Begin"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Begin 메서드. 애니메이션이 시작되는 시점을 정의하는 begin 속성을 설정합니다."
type: docs
weight: 610
url: /ko/net/aspose.svg.builder/svgbuilderextensions/begin/
---
## SVGBuilderExtensions.Begin<TBuilder> method

'begin' 속성을 설정하고, 애니메이션이 시작되는 시점을 정의합니다.

```csharp
public static TBuilder Begin<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 구성 | 타이밍 값을 구성하기 위한 대리자입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [TimingValueBuilder](../../timingvaluebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
