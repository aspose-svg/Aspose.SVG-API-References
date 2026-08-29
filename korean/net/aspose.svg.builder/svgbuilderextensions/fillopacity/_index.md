---
title: "SVGBuilderExtensions.FillOpacity"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions FillOpacity 메서드. SVG 요소의 fill-opacity 속성을 설정합니다. 값은 0.0(완전 투명)에서 1.0(완전 불투명) 사이여야 합니다"
type: docs
weight: 820
url: /ko/net/aspose.svg.builder/svgbuilderextensions/fillopacity/
---
## SVGBuilderExtensions.FillOpacity<TBuilder> method

SVG 요소의 'fill-opacity' 속성을 설정합니다. 값은 0.0(완전 투명)과 1.0(완전 불투명) 사이여야 합니다.

```csharp
public static TBuilder FillOpacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| opacity | 설정할 불투명도 값입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentOutOfRangeException | 불투명도가 유효 범위에 없을 경우 발생합니다. |

### 또 보기

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
