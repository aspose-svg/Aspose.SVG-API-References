---
title: "SVGBuilderExtensions.LengthAdjust"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions LengthAdjust 메서드. 텍스트 내용의 길이 조정 방법을 설정합니다."
type: docs
weight: 1090
url: /ko/net/aspose.svg.builder/svgbuilderextensions/lengthadjust/
---
## SVGBuilderExtensions.LengthAdjust<TBuilder> method

텍스트 내용에 대한 길이 조정 방법을 설정합니다.

```csharp
public static TBuilder LengthAdjust<TBuilder>(this TBuilder builder, LengthAdjust value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 길이 조정 방법. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

## 비고

이 메서드는 텍스트 길이를 조정하는 방식을 결정하는 'lengthAdjust' 속성을 설정합니다. 간격으로 조정하거나 스케일링으로 조정합니다.

### 또 보기

* enum [LengthAdjust](../../lengthadjust/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
