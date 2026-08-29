---
title: "SVGBuilderExtensions.OnCopy"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions OnCopy 메서드. SVG 요소에서 내용이 복사될 때 실행되는 스크립트를 정의하는 oncopy 이벤트 속성을 설정합니다."
type: docs
weight: 1270
url: /ko/net/aspose.svg.builder/svgbuilderextensions/oncopy/
---
## SVGBuilderExtensions.OnCopy<TBuilder> method

'oncopy' 이벤트 속성을 설정하고, SVG 요소에서 내용이 복사될 때 실행될 스크립트를 정의합니다.

```csharp
public static TBuilder OnCopy<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 복사 이벤트에서 실행할 JavaScript 함수 또는 스크립트입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
