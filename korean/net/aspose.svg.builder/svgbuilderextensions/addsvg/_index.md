---
title: "SVGBuilderExtensions.AddSvg"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddSvg 메서드. 빌더에 svg 확장 가능한 벡터 그래픽 요소 구성을 추가합니다."
type: docs
weight: 500
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addsvg/
---
## SVGBuilderExtensions.AddSvg<TBuilder> method

빌더에 'svg' (확장 가능한 벡터 그래픽) 요소 구성을 추가합니다.

```csharp
public static TBuilder AddSvg<TBuilder>(this TBuilder builder, 
    Action<SVGSVGElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'svg' 요소에 대한 구성 작업. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGSVGElementBuilder](../../svgsvgelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
