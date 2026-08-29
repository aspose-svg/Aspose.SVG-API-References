---
title: "SVGBuilderExtensions.X"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions X 메서드. SVG 요소의 x 속성을 설정합니다."
type: docs
weight: 2360
url: /ko/net/aspose.svg.builder/svgbuilderextensions/x/
---
## X<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#x_1}

'x' 속성을 SVG 요소에 설정합니다.

```csharp
public static TBuilder X<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IXAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 값 | 'x' 속성의 값입니다. |
| type | 길이 측정 유형입니다(기본값은 픽셀). |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IXAttributeSetter](../../ixattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## X<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#x}

텍스트 내용을 x축을 따라 위치시키기 위해 'x' 속성을 설정합니다.

```csharp
public static TBuilder X<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| type | 값들의 길이 단위 유형입니다. |
| values | x축 위치 값들입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

## 비고

이 메서드는 텍스트 요소의 수평 위치를 결정하는 'x' 속성을 설정합니다.

### 또 보기

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
