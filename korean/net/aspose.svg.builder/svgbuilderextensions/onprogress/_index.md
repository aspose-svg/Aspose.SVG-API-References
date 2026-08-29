---
title: "SVGBuilderExtensions.OnProgress"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions OnProgress 메서드. 진행 중인 프로세스의 진행 상황을 나타내는 이벤트를 처리하기 위해 onprogress 이벤트 속성을 설정합니다."
type: docs
weight: 1680
url: /ko/net/aspose.svg.builder/svgbuilderextensions/onprogress/
---
## SVGBuilderExtensions.OnProgress<TBuilder> method

진행 중인 프로세스의 진행 상황을 나타내는 이벤트를 처리하기 위해 'onprogress' 이벤트 속성을 설정합니다.

```csharp
public static TBuilder OnProgress<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 진행 중인 프로세스의 진행 상황을 나타내기 위해 실행할 JavaScript 함수 또는 스크립트입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
