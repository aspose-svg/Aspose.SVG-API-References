---
title: "SVGBuilderExtensions.OnFocusIn"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions OnFocusIn 메서드. 요소에서 포커스 인 이벤트를 처리하기 위한 onfocusin 이벤트 속성을 설정합니다."
type: docs
weight: 1450
url: /ko/net/aspose.svg.builder/svgbuilderextensions/onfocusin/
---
## SVGBuilderExtensions.OnFocusIn<TBuilder> method

요소에서 포커스 인 이벤트를 처리하기 위해 'onfocusin' 이벤트 속성을 설정합니다.

```csharp
public static TBuilder OnFocusIn<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 요소가 포커스를 받을 때 실행되는 JavaScript 함수 또는 스크립트이며, 일반적으로 'onfocus' 이벤트 이전에 실행됩니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

## 비고

'onfocusin' 이벤트는 요소가 포커스를 받으려 할 때 트리거됩니다. 이 이벤트는 버블링을 지원하고 자식 요소의 포커스 변화도 감지할 수 있다는 점에서 'onfocus'와 다릅니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
