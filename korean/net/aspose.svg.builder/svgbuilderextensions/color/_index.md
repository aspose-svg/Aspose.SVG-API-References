---
title: "SVGBuilderExtensions.Color"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Color 메서드. 사용자 지정 구성을 사용하여 SVG 요소의 color 속성을 설정합니다."
type: docs
weight: 670
url: /ko/net/aspose.svg.builder/svgbuilderextensions/color/
---
## Color<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#color}

사용자 정의 구성을 사용하여 SVG 요소에 'color' 속성을 설정합니다.

```csharp
public static TBuilder Color<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 색상을 구성하기 위한 대리자입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [ColorBuilder](../../colorbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Color<TBuilder>(*this TBuilder, Color*) {#color_1}

색상 값을 사용하여 SVG 요소에 'color' 속성을 설정합니다.

```csharp
public static TBuilder Color<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| colorValue | 설정할 색상 값입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
