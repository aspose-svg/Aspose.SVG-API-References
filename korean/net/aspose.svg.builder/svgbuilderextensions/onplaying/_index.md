---
title: "SVGBuilderExtensions.OnPlaying"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions OnPlaying 메서드. 미디어가 일시 정지되거나 버퍼링을 위해 중지된 후 다시 활성 재생될 때 이벤트를 처리하기 위해 onplaying 이벤트 속성을 설정합니다."
type: docs
weight: 1670
url: /ko/net/aspose.svg.builder/svgbuilderextensions/onplaying/
---
## SVGBuilderExtensions.OnPlaying<TBuilder> method

미디어가 일시 정지되거나 버퍼링을 위해 중지된 후 활발히 재생될 때 발생하는 이벤트를 처리하기 위해 'onplaying' 이벤트 속성을 설정합니다.

```csharp
public static TBuilder OnPlaying<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 미디어가 활성 재생될 때 실행되는 JavaScript 함수 또는 스크립트입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
