---
title: "SVGBuilderExtensions.Rect"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Rect 메서드. SVG 요소에 사각형을 정의하기 위해 x, y, width 및 height 속성을 설정합니다."
type: docs
weight: 1920
url: /ko/net/aspose.svg.builder/svgbuilderextensions/rect/
---
## SVGBuilderExtensions.Rect<TBuilder> method

SVG 요소에 사각형을 정의하기 위해 'x', 'y', 'width', 'height' 속성을 설정합니다.

```csharp
public static TBuilder Rect<TBuilder>(this TBuilder builder, double x, double y, double width, 
    double height, LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRectAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| x | 사각형의 x 좌표입니다. |
| y | 사각형의 y 좌표입니다. |
| width | 사각형의 너비입니다. |
| height | 사각형의 높이입니다. |
| type | 모든 차원의 길이 측정 유형입니다(기본값은 픽셀). |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRectAttributeSetter](../../irectattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
