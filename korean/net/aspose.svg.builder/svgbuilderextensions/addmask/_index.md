---
title: "SVGBuilderExtensions.AddMask"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddMask 메서드. 마스크 요소 구성을 빌더에 추가합니다."
type: docs
weight: 380
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addmask/
---
## SVGBuilderExtensions.AddMask<TBuilder> method

빌더에 'mask' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddMask<TBuilder>(this TBuilder builder, 
    Action<SVGMaskElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'mask' 요소에 대한 구성 작업입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGMaskElementBuilder](../../svgmaskelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
