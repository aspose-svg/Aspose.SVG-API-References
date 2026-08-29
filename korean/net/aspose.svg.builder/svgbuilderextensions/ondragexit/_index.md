---
title: "SVGBuilderExtensions.OnDragExit"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions OnDragExit 메서드. 끌어다 놓은 항목이 유효한 드롭 대상에서 벗어날 때를 처리하기 위해 ondragexit 이벤트 속성을 설정합니다."
type: docs
weight: 1340
url: /ko/net/aspose.svg.builder/svgbuilderextensions/ondragexit/
---
## SVGBuilderExtensions.OnDragExit<TBuilder> method

드래그된 항목이 유효한 드롭 대상에서 나갈 때를 처리하기 위해 'ondragexit' 이벤트 속성을 설정합니다.

```csharp
public static TBuilder OnDragExit<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 끌어다 놓은 항목이 유효한 드롭 대상에서 벗어날 때 실행할 JavaScript 함수 또는 스크립트입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
