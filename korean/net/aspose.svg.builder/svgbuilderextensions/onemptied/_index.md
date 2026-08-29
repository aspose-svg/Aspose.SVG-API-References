---
title: "SVGBuilderExtensions.OnEmptied"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions OnEmptied 메서드. 미디어 요소의 소스가 비워지는 것을 처리하기 위한 onemptied 이벤트 속성을 설정합니다."
type: docs
weight: 1400
url: /ko/net/aspose.svg.builder/svgbuilderextensions/onemptied/
---
## SVGBuilderExtensions.OnEmptied<TBuilder> method

미디어 요소의 소스를 비우는 것을 처리하기 위해 'onemptied' 이벤트 속성을 설정합니다.

```csharp
public static TBuilder OnEmptied<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 미디어 요소의 소스가 비워질 때 실행할 JavaScript 함수 또는 스크립트입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
