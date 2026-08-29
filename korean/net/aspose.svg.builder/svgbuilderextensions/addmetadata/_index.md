---
title: "SVGBuilderExtensions.AddMetadata"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddMetadata 메서드. 빌더에 메타데이터 요소 구성을 추가합니다. 메타데이터 요소는 SVG 콘텐츠에 메타데이터를 추가하는 데 사용됩니다."
type: docs
weight: 390
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addmetadata/
---
## SVGBuilderExtensions.AddMetadata<TBuilder,TElement> method

빌더에 'metadata' 요소 구성을 추가합니다. 'metadata' 요소는 SVG 콘텐츠에 메타데이터를 추가하는 데 사용됩니다.

```csharp
public static TBuilder AddMetadata<TBuilder, TElement>(this TBuilder builder, 
    Action<SVGMetadataElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| TElement | SVG 모델에서 'metadata' 요소를 나타내는 타입. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'metadata' 요소에 대한 구성 액션. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGMetadataElementBuilder](../../svgmetadataelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
