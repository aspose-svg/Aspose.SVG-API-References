---
title: "SVGBuilderExtensions.OnFocusOut"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions OnFocusOut 메서드. 요소에서 포커스가 해제될 때 발생하는 이벤트를 처리하기 위해 onfocusout 이벤트 속성을 설정합니다."
type: docs
weight: 1460
url: /ko/net/aspose.svg.builder/svgbuilderextensions/onfocusout/
---
## SVGBuilderExtensions.OnFocusOut<TBuilder> method

요소에서 포커스 아웃 이벤트를 처리하기 위해 'onfocusout' 이벤트 속성을 설정합니다.

```csharp
public static TBuilder OnFocusOut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 요소가 포커스를 잃을 때, 일반적으로 'onblur' 이벤트 전에 실행되는 JavaScript 함수 또는 스크립트입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

## 비고

'onfocusout' 이벤트는 요소가 포커스를 잃으려 할 때 트리거됩니다. 'onfocusin'과 유사하게, 이 이벤트는 버블링을 지원하며 자식 요소의 포커스 변화도 감지하는 데 사용할 수 있습니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
