---
title: "SVGBuilderExtensions.SetPreserveAspectRatio"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions SetPreserveAspectRatio 메서드. SVG 요소에 대한 preserveAspectRatio 속성을 설정합니다."
type: docs
weight: 2020
url: /ko/net/aspose.svg.builder/svgbuilderextensions/setpreserveaspectratio/
---
## SVGBuilderExtensions.SetPreserveAspectRatio<TBuilder> method

SVG 요소에 'preserveAspectRatio' 속성을 설정합니다.

```csharp
public static TBuilder SetPreserveAspectRatio<TBuilder>(this TBuilder builder, 
    AspectRatioAlign align, AspectRatioScaling meetOrSlice = AspectRatioScaling.Meet)
    where TBuilder : ISVGElementBuilder, IPreserveAspectRatioAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| align | 종횡비에 대한 정렬 설정입니다. |
| meetOrSlice | 종횡비가 유지되는 방식을 지정합니다(기본값은 'Meet'입니다). |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [AspectRatioAlign](../../aspectratioalign/)
* enum [AspectRatioScaling](../../aspectratioscaling/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../../ipreserveaspectratioattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
