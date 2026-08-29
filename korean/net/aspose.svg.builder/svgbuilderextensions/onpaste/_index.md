---
title: "SVGBuilderExtensions.OnPaste"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions OnPaste 메서드. SVG 요소에 내용이 붙여넣어질 때 실행될 스크립트를 정의하는 onpaste 이벤트 속성을 설정합니다."
type: docs
weight: 1640
url: /ko/net/aspose.svg.builder/svgbuilderextensions/onpaste/
---
## SVGBuilderExtensions.OnPaste<TBuilder> method

SVG 요소에 내용이 붙여넣어질 때 실행될 스크립트를 정의하여 'onpaste' 이벤트 속성을 설정합니다.

```csharp
public static TBuilder OnPaste<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 붙여넣기 이벤트에서 실행할 JavaScript 함수 또는 스크립트. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
