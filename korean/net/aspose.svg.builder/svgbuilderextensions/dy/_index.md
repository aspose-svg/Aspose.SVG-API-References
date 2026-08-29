---
title: "SVGBuilderExtensions.Dy"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Dy 메서드. 텍스트 내용에 대한 여러 수직 조정 값을 설정합니다."
type: docs
weight: 780
url: /ko/net/aspose.svg.builder/svgbuilderextensions/dy/
---
## Dy<TBuilder>(*this TBuilder, double[], [LengthType](../../lengthtype/)*) {#dy_1}

텍스트 내용에 대한 여러 수직 조정 값을 설정합니다.

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double[] values, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| values | 수직 조정 값들의 배열입니다. |
| type | 값들의 길이 단위 유형입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

## 비고

이 메서드는 여러 값을 사용하여 'dy' 속성을 설정하며, 각 문자 또는 텍스트 세그먼트에 대한 개별 수직 조정을 가능하게 합니다.

### 또 보기

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dy<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dy}

텍스트 내용에 대한 단일 수직 조정 값을 설정합니다.

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 수직 조정 값입니다. |
| type | 값의 길이 단위 유형입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

## 비고

이 메서드는 단일 값을 사용하여 'dy' 속성을 설정하고 텍스트 내용의 수직 위치를 조정합니다.

### 또 보기

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
