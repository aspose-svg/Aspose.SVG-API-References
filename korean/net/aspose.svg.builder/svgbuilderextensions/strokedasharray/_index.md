---
title: "SVGBuilderExtensions.StrokeDashArray"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions StrokeDashArray 메서드. 스트로크를 그리는 데 사용되는 대시와 간격 패턴을 정의하는 SVG 요소의 stroke-dasharray 속성을 설정합니다."
type: docs
weight: 2090
url: /ko/net/aspose.svg.builder/svgbuilderextensions/strokedasharray/
---
## StrokeDashArray<TBuilder>(*this TBuilder, params double[]*) {#strokedasharray_1}

SVG 요소의 'stroke-dasharray' 속성을 설정하고, 스트로크를 그릴 때 사용되는 대시와 간격의 패턴을 정의합니다.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, params double[] dashArray)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| dashArray | 대시 길이들의 배열입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## StrokeDashArray<TBuilder>(*this TBuilder, [Dash](../../dash/)*) {#strokedasharray}

미리 정의된 대시 패턴을 사용하여 SVG 요소의 'stroke-dasharray' 속성을 설정합니다.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, Dash value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 값 | 설정할 대시 패턴입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [Dash](../../dash/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
