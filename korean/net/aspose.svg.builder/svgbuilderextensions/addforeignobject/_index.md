---
title: "SVGBuilderExtensions.AddForeignObject"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddForeignObject 메서드. 빌더에 foreignObject 요소 구성을 추가합니다."
type: docs
weight: 310
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addforeignobject/
---
## SVGBuilderExtensions.AddForeignObject<TBuilder> method

빌더에 'foreignObject' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddForeignObject<TBuilder>(this TBuilder builder, 
    Action<SVGForeignObjectElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'foreignObject' 요소에 대한 구성 작업. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGForeignObjectElementBuilder](../../svgforeignobjectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
