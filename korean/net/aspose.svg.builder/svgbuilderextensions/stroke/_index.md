---
title: "SVGBuilderExtensions.Stroke"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Stroke 메서드. 사용자 정의 페인트 구성을 사용하여 SVG 요소의 stroke 속성을 설정합니다"
type: docs
weight: 2080
url: /ko/net/aspose.svg.builder/svgbuilderextensions/stroke/
---
## Stroke<TBuilder>(*this TBuilder, Action&lt;PaintBuilder&gt;*) {#stroke_1}

사용자 지정 페인트 구성을 사용하여 SVG 요소의 'stroke' 속성을 설정합니다.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Action<PaintBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 페인트를 구성하기 위한 대리자입니다. |

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

## Stroke<TBuilder>(*this TBuilder, Color*) {#stroke_2}

특정 색상을 사용하여 SVG 요소의 'stroke' 속성을 설정합니다.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Color color)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 색상 | stroke에 사용할 색상입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Stroke<TBuilder>(*this TBuilder, [Paint](../../paint/)*) {#stroke}

미리 정의된 페인트 값을 사용하여 SVG 요소의 'stroke' 속성을 설정합니다.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Paint paint)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 페인트 | 설정할 페인트 값입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [Paint](../../paint/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
