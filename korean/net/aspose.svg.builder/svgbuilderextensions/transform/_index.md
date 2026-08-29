---
title: "SVGBuilderExtensions.Transform"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Transform 메서드. SVG 요소의 transform 속성을 설정합니다."
type: docs
weight: 2260
url: /ko/net/aspose.svg.builder/svgbuilderextensions/transform/
---
## SVGBuilderExtensions.Transform<TBuilder> method

SVG 요소에 'transform' 속성을 설정합니다.

```csharp
public static TBuilder Transform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, ITransformAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | SVG 변환을 구성하는 함수. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITransformAttributeSetter](../../itransformattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
