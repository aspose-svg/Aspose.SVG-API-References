---
title: "SVGBuilderExtensions.Dx"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Dx 메서드. 텍스트의 각 문자 수평 위치를 조정하기 위해 dx 속성을 설정합니다"
type: docs
weight: 770
url: /ko/net/aspose.svg.builder/svgbuilderextensions/dx/
---
## Dx<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#dx}

텍스트의 각 문자 수평 위치를 조정하기 위해 'dx' 속성을 설정합니다.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| type | 값들의 길이 단위 유형입니다. |
| values | 각 문자에 대한 수평 조정 값. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

## 비고

이 메서드는 텍스트 내 문자들의 수평 간격을 정밀하게 제어할 수 있게 합니다.

### 또 보기

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dx<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dx_1}

텍스트 내용에 대한 단일 수평 조정 값을 설정합니다.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 수평 조정 값. |
| type | 값의 길이 단위 유형입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

## 비고

이 메서드는 단일 값으로 'dx' 속성을 설정하여 텍스트 내용의 수평 위치를 조정합니다.

### 또 보기

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
