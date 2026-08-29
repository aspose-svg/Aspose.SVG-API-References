---
title: "SVGBuilderExtensions.AddContent"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddContent 메서드. SVG 요소에 텍스트 내용을 추가합니다."
type: docs
weight: 90
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addcontent/
---
## SVGBuilderExtensions.AddContent<TBuilder> method

SVG 요소에 텍스트 콘텐츠를 추가합니다.

```csharp
public static TBuilder AddContent<TBuilder>(this TBuilder builder, string text)
    where TBuilder : ISVGElementBuilder, ITextContentSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 텍스트 | 요소에 추가될 텍스트입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

## 비고

이 메서드는 텍스트 내용을 SVG 요소에 직접 추가할 수 있게 해줍니다. 텍스트 데이터를 포함하는 요소에 유용합니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentSetter](../../itextcontentsetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
