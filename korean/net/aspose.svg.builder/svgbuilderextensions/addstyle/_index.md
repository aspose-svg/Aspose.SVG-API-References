---
title: "SVGBuilderExtensions.AddStyle"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddStyle 메서드. 빌더에 스타일 요소 구성을 추가합니다."
type: docs
weight: 490
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addstyle/
---
## SVGBuilderExtensions.AddStyle<TBuilder> method

빌더에 'style' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddStyle<TBuilder>(this TBuilder builder, 
    Action<SVGStyleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'style' 요소에 대한 구성 작업. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGStyleElementBuilder](../../svgstyleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
