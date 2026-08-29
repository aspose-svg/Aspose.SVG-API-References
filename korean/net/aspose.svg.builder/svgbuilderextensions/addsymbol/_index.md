---
title: "SVGBuilderExtensions.AddSymbol"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddSymbol 메서드. 빌더에 symbol 요소 구성을 추가합니다"
type: docs
weight: 520
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addsymbol/
---
## SVGBuilderExtensions.AddSymbol<TBuilder> method

빌더에 'symbol' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddSymbol<TBuilder>(this TBuilder builder, 
    Action<SVGSymbolElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'symbol' 요소에 대한 구성 작업입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGSymbolElementBuilder](../../svgsymbolelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
