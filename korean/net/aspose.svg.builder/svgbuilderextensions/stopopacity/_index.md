---
title: "SVGBuilderExtensions.StopOpacity"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions StopOpacity 메서드. 그라디언트 스톱에서 불투명도를 정의하는 SVG 요소의 stop-opacity 속성을 설정합니다."
type: docs
weight: 2070
url: /ko/net/aspose.svg.builder/svgbuilderextensions/stopopacity/
---
## SVGBuilderExtensions.StopOpacity<TBuilder> method

그라디언트 정지점에서 불투명도를 정의하는 'stop-opacity' 속성을 SVG 요소에 설정합니다.

```csharp
public static TBuilder StopOpacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| opacity | opacity 값 (완전 투명은 0.0, 완전 불투명은 1.0). |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
