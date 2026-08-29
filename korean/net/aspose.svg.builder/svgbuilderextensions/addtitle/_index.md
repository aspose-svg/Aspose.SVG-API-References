---
title: "SVGBuilderExtensions.AddTitle"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddTitle 메서드. 빌더에 title 요소 구성을 추가합니다. title 요소는 SVG 콘텐츠에 제목을 제공하는 데 사용됩니다."
type: docs
weight: 540
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addtitle/
---
## SVGBuilderExtensions.AddTitle<TBuilder> method

빌더에 'title' 요소 구성을 추가합니다. 'title' 요소는 SVG 콘텐츠에 제목을 제공하는 데 사용됩니다.

```csharp
public static TBuilder AddTitle<TBuilder>(this TBuilder builder, 
    Action<SVGTitleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'title' 요소에 대한 구성 액션입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGTitleElementBuilder](../../svgtitleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
