---
title: "SVGBuilderExtensions.Rotate"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Rotate 메서드. 텍스트 내용의 개별 문자 또는 세그먼트에 대한 회전 각도를 설정합니다."
type: docs
weight: 2000
url: /ko/net/aspose.svg.builder/svgbuilderextensions/rotate/
---
## Rotate<TBuilder>(*this TBuilder, params double[]*) {#rotate_1}

텍스트 내용의 개별 문자 또는 구간에 대한 회전 각도를 설정합니다.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| values | 도 단위의 회전 각도 배열입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

## 비고

이 메서드는 여러 값을 사용하여 'rotate' 속성을 설정하며, 각 문자 또는 텍스트 세그먼트별 개별 회전을 가능하게 합니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Rotate<TBuilder>(*this TBuilder, double*) {#rotate}

전체 텍스트 내용에 대한 단일 회전 각도를 설정합니다.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, double value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 도 단위의 회전 각도입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

## 비고

이 메서드는 단일 값을 사용하여 'rotate' 속성을 설정하고, 모든 텍스트 내용에 동일한 회전 각도를 적용합니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
