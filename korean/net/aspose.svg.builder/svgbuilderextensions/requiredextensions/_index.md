---
title: "SVGBuilderExtensions.RequiredExtensions"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions RequiredExtensions 메서드. SVG 요소에 requiredExtensions 속성을 설정합니다. 이 속성은 SVG 문서 조각을 처리하기 위해 필요한 확장자를 지정합니다."
type: docs
weight: 1970
url: /ko/net/aspose.svg.builder/svgbuilderextensions/requiredextensions/
---
## SVGBuilderExtensions.RequiredExtensions<TBuilder> method

SVG 요소에 'requiredExtensions' 속성을 설정합니다. 이 속성은 SVG 문서 조각을 처리하기 위해 필요한 확장자를 지정합니다.

```csharp
public static TBuilder RequiredExtensions<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IConditionalProcessingAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 속성이 설정되는 SVG 요소 빌더입니다. |
| 값 | 필요한 확장자를 나타내는 문자열 값입니다. |

### 반환 값

메서드 체이닝을 위한 원본 SVG 요소 빌더입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../../iconditionalprocessingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
