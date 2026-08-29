---
title: "SVGBuilderExtensions.ViewBox"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions ViewBox 메서드. SVG 요소의 viewBox 속성을 설정합니다."
type: docs
weight: 2300
url: /ko/net/aspose.svg.builder/svgbuilderextensions/viewbox/
---
## SVGBuilderExtensions.ViewBox<TBuilder> method

'viewBox' 속성을 SVG 요소에 설정합니다.

```csharp
public static TBuilder ViewBox<TBuilder>(this TBuilder builder, double minX, double minY, 
    double width, double height)
    where TBuilder : ISVGElementBuilder, IViewBoxAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| minX | viewBox의 최소 X 좌표입니다. |
| minY | viewBox의 최소 Y 좌표입니다. |
| width | viewBox의 너비입니다. |
| height | viewBox의 높이입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IViewBoxAttributeSetter](../../iviewboxattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
