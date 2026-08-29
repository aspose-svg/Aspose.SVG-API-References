---
title: "SVGBuilderExtensions.SystemLanguage"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions SystemLanguage 메서드. SVG 요소에 systemLanguage 속성을 설정합니다. 이 속성은 SVG 문서 조각이 의도된 언어 기본 설정을 지정합니다."
type: docs
weight: 2170
url: /ko/net/aspose.svg.builder/svgbuilderextensions/systemlanguage/
---
## SVGBuilderExtensions.SystemLanguage<TBuilder> method

SVG 요소에 'systemLanguage' 속성을 설정합니다. 이 속성은 SVG 문서 조각이 의도된 언어 선호도를 지정합니다.

```csharp
public static TBuilder SystemLanguage<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IConditionalProcessingAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 속성이 설정되는 SVG 요소 빌더입니다. |
| 값 | 언어 기본 설정을 나타내는 문자열 값이며, 일반적으로 언어 태그 형식입니다. |

### 반환 값

메서드 체이닝을 위한 원본 SVG 요소 빌더입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../../iconditionalprocessingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
