---
title: "SVGBuilderExtensions.AddSet"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddSet 메서드. 빌더에 set 요소 구성을 추가합니다."
type: docs
weight: 470
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addset/
---
## SVGBuilderExtensions.AddSet<TBuilder> method

빌더에 'set' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddSet<TBuilder>(this TBuilder builder, 
    Action<SVGSetElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IBaseAnimationElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'set' 요소에 대한 구성 작업입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGSetElementBuilder](../../svgsetelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IBaseAnimationElementBuilder](../../ibaseanimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
