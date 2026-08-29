---
title: "SVGBuilderExtensions.OnInvalid"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions OnInvalid 메서드. 폼 요소에서 잘못된 이벤트를 처리하기 위한 oninvalid 이벤트 속성을 설정합니다."
type: docs
weight: 1480
url: /ko/net/aspose.svg.builder/svgbuilderextensions/oninvalid/
---
## SVGBuilderExtensions.OnInvalid<TBuilder> method

폼 요소에서 잘못된 이벤트를 처리하기 위해 'oninvalid' 이벤트 속성을 설정합니다.

```csharp
public static TBuilder OnInvalid<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 요소 값이 유효하지 않을 때 실행할 JavaScript 함수 또는 스크립트. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
