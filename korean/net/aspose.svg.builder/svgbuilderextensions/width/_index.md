---
title: "SVGBuilderExtensions.Width"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Width 메서드. SVG 요소의 width 속성을 설정합니다."
type: docs
weight: 2330
url: /ko/net/aspose.svg.builder/svgbuilderextensions/width/
---
## SVGBuilderExtensions.Width<TBuilder> method

'width' 속성을 SVG 요소에 설정합니다.

```csharp
public static TBuilder Width<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IWidthAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 값 | 'width' 속성의 값입니다. |
| type | 길이 측정 유형입니다(기본값은 픽셀). |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IWidthAttributeSetter](../../iwidthattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
