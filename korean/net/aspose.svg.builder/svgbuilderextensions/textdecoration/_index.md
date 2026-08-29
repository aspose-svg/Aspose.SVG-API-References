---
title: "SVGBuilderExtensions.TextDecoration"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions TextDecoration 메서드. 텍스트에 추가되는 장식을 정의하는 SVG 요소의 text-decoration 속성을 설정합니다."
type: docs
weight: 2210
url: /ko/net/aspose.svg.builder/svgbuilderextensions/textdecoration/
---
## SVGBuilderExtensions.TextDecoration<TBuilder> method

SVG 요소에 'text-decoration' 속성을 설정하고, 텍스트에 추가되는 장식을 정의합니다.

```csharp
public static TBuilder TextDecoration<TBuilder>(this TBuilder builder, bool underline = false, 
    bool overline = false, bool lineThrough = false, bool blink = false)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 밑줄 | 텍스트에 밑줄을 표시할지 여부를 지정합니다. |
| 윗줄 | 텍스트에 윗줄을 표시할지 여부를 지정합니다. |
| 취소선 | 텍스트에 취소선을 표시할지 여부를 지정합니다. |
| 깜박임 | 텍스트가 깜박일지 여부를 지정합니다(사용을 권장하지 않음). |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
