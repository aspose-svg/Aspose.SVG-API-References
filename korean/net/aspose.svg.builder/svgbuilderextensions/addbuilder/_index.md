---
title: "SVGBuilderExtensions.AddBuilder"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddBuilder 메서드. 기존 SVG 요소 빌더를 현재 SVG 요소 빌더에 추가합니다. 이 메서드는 미리 정의된 SVG 요소 빌더를 현재 빌더에 포함시키는 데 사용됩니다."
type: docs
weight: 60
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addbuilder/
---
## SVGBuilderExtensions.AddBuilder<TBuilder,TElementBuilder> method

기존 SVG 요소 빌더를 현재 SVG 요소 빌더에 추가합니다. 이 메서드는 미리 정의된 SVG 요소 빌더를 현재 빌더에 포함시키는 데 사용됩니다.

```csharp
public static TBuilder AddBuilder<TBuilder, TElementBuilder>(this TBuilder builder, 
    TElementBuilder elementBuilder)
    where TBuilder : ISVGElementBuilder
    where TElementBuilder : ISVGElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| TElementBuilder | 구성할 SVG 요소 빌더의 유형. TElementBuilder는 ISVGElementBuilder를 구현해야 합니다. |
| 빌더 | 다른 요소 빌더가 추가되는 SVG 요소 빌더. |
| elementBuilder | 추가될 SVG 요소 빌더. |

### 반환 값

메서드 체이닝을 위한 원본 SVG 요소 빌더입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
