---
title: "SVGBuilderExtensions.Values"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Values 메서드. 애니메이션 동안 사용될 값 집합을 지정하는 values 속성을 설정합니다."
type: docs
weight: 2290
url: /ko/net/aspose.svg.builder/svgbuilderextensions/values/
---
## SVGBuilderExtensions.Values<TBuilder> method

'values' 속성을 설정하여 애니메이션 진행 중에 사용될 값들의 집합을 지정합니다.

```csharp
public static TBuilder Values<TBuilder>(this TBuilder builder, params string[] values)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| values | 애니메이션에 대한 값 배열입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
