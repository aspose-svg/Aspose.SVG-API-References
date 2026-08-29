---
title: "SVGBuilderExtensions.TextLength"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions TextLength 메서드. 텍스트 내용의 정확한 길이를 설정합니다"
type: docs
weight: 2220
url: /ko/net/aspose.svg.builder/svgbuilderextensions/textlength/
---
## SVGBuilderExtensions.TextLength<TBuilder> method

텍스트 내용의 정확한 길이를 설정합니다.

```csharp
public static TBuilder TextLength<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 텍스트의 길이. |
| type | 값의 길이 단위 유형입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

## 비고

이 메서드는 'textLength' 속성을 설정하여 텍스트 내용의 원하는 길이를 지정하며, 자연스러운 텍스트 길이를 대체할 수 있습니다.

### 또 보기

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
