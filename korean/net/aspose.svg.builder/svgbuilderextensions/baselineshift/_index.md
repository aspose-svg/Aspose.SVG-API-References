---
title: "SVGBuilderExtensions.BaselineShift"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions BaselineShift 메서드. 미리 정의된 값을 사용하여 SVG 요소의 baseline-shift 속성을 설정합니다."
type: docs
weight: 600
url: /ko/net/aspose.svg.builder/svgbuilderextensions/baselineshift/
---
## BaselineShift<TBuilder>(*this TBuilder, [BaseLineShift](../../baselineshift/)*) {#baselineshift}

미리 정의된 값을 사용하여 SVG 요소에 대한 'baseline-shift' 속성을 설정합니다.

```csharp
public static TBuilder BaselineShift<TBuilder>(this TBuilder builder, BaseLineShift value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 값 | 설정할 baseline shift 값입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [BaseLineShift](../../baselineshift/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## BaselineShift<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#baselineshift_1}

숫자 값을 사용하여 SVG 요소에 대한 'baseline-shift' 속성을 설정합니다.

```csharp
public static TBuilder BaselineShift<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 값 | baseline shift의 숫자 값입니다. |
| type | 길이 단위 유형입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
