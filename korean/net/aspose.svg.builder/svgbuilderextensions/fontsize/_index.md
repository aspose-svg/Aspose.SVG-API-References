---
title: "SVGBuilderExtensions.FontSize"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions FontSize 메서드. 숫자 값과 특정 길이 유형을 사용하여 SVG 요소의 font-size 속성을 설정합니다"
type: docs
weight: 890
url: /ko/net/aspose.svg.builder/svgbuilderextensions/fontsize/
---
## FontSize<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#fontsize_1}

숫자 값과 특정 길이 유형을 사용하여 SVG 요소의 'font-size' 속성을 설정합니다.

```csharp
public static TBuilder FontSize<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 값 | 설정할 글꼴 크기 값입니다. |
| type | 길이 유형 (예: px, em). |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## FontSize<TBuilder>(*this TBuilder, [FontSize](../../fontsize/)*) {#fontsize}

미리 정의된 글꼴 크기 값을 사용하여 SVG 요소의 'font-size' 속성을 설정합니다.

```csharp
public static TBuilder FontSize<TBuilder>(this TBuilder builder, FontSize value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 값 | 설정할 미리 정의된 글꼴 크기 값입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [FontSize](../../fontsize/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
