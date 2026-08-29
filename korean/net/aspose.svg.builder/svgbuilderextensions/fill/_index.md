---
title: "SVGBuilderExtensions.Fill"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Fill 메서드. 애니메이션 활성 기간 외에 스타일을 적용하는 방식을 정의하는 fill 속성을 설정합니다."
type: docs
weight: 810
url: /ko/net/aspose.svg.builder/svgbuilderextensions/fill/
---
## Fill<TBuilder>(*this TBuilder, [AnimationFill](../../animationfill/)*) {#fill}

'fill' 속성을 설정하여 애니메이션이 활성 기간 외에 스타일을 적용하는 방식을 정의합니다.

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, AnimationFill value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 애니메이션의 fill 동작. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [AnimationFill](../../animationfill/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Fill<TBuilder>(*this TBuilder, Action&lt;PaintBuilder&gt;*) {#fill_2}

사용자 지정 구성으로 SVG 요소의 'fill' 속성을 설정합니다.

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, Action<PaintBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | PaintBuilder를 구성하기 위한 대리자. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [PaintBuilder](../../paintbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Fill<TBuilder>(*this TBuilder, Color*) {#fill_3}

색상을 사용하여 SVG 요소의 'fill' 속성을 설정합니다.

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, Color color)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 색상 | fill로 설정할 색상. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Fill<TBuilder>(*this TBuilder, [Paint](../../paint/)*) {#fill_1}

미리 정의된 Paint 열거형 값을 사용하여 SVG 요소의 'fill' 속성을 설정합니다.

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, Paint paint)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 페인트 | 설정할 Paint 열거형 값. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [Paint](../../paint/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
