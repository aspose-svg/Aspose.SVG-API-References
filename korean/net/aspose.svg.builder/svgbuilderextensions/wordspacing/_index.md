---
title: "SVGBuilderExtensions.WordSpacing"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions WordSpacing 메서드. SVG 요소에 대한 word-spacing 속성을 설정하여 단어 사이의 간격 동작을 지정합니다."
type: docs
weight: 2340
url: /ko/net/aspose.svg.builder/svgbuilderextensions/wordspacing/
---
## WordSpacing<TBuilder>(*this TBuilder, [Spacing](../../spacing/)*) {#wordspacing}

'word-spacing' 속성을 SVG 요소에 설정하여 단어 사이의 간격 동작을 지정합니다.

```csharp
public static TBuilder WordSpacing<TBuilder>(this TBuilder builder, Spacing value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 값 | 사전 정의된 단어 간격 값입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [Spacing](../../spacing/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## WordSpacing<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#wordspacing_1}

'word-spacing' 속성을 SVG 요소에 설정하여 사용자 정의 값으로 단어 사이의 간격 동작을 지정합니다.

```csharp
public static TBuilder WordSpacing<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 값 | 단어 간격 값입니다. |
| type | 간격 값의 단위 유형입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
