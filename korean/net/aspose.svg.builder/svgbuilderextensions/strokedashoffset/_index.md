---
title: "SVGBuilderExtensions.StrokeDashoffset"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions StrokeDashoffset 메서드. 스트로크 대시 배열 시작 오프셋을 정의하는 stroke-dashoffset 속성을 SVG 요소에 설정합니다."
type: docs
weight: 2100
url: /ko/net/aspose.svg.builder/svgbuilderextensions/strokedashoffset/
---
## SVGBuilderExtensions.StrokeDashoffset<TBuilder> method

SVG 요소의 'stroke-dashoffset' 속성을 설정하고, 스트로크 대시 배열 시작 지점의 오프셋을 정의합니다.

```csharp
public static TBuilder StrokeDashoffset<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 값 | 대시 오프셋 값. |
| type | 오프셋 값의 단위 유형입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
