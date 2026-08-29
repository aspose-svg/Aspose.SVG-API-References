---
title: "SVGBuilderExtensions.OnUnload"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions OnUnload 메서드. SVG 문서가 언로드될 때 실행될 스크립트를 정의하는 onunload 이벤트 속성을 설정합니다."
type: docs
weight: 1830
url: /ko/net/aspose.svg.builder/svgbuilderextensions/onunload/
---
## SVGBuilderExtensions.OnUnload<TBuilder> method

SVG 문서가 언로드될 때 실행되는 스크립트를 정의하는 'onunload' 이벤트 속성을 설정합니다.

```csharp
public static TBuilder OnUnload<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentEventAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 문서가 언로드될 때 실행할 JavaScript 함수 또는 스크립트. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentEventAttributeSetter](../../idocumenteventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
