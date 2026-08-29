---
title: "SVGBuilderExtensions.SetAttribute"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions SetAttribute 메서드. SVG 요소에 속성을 설정합니다. 이 메서드는 빌드 중인 SVG 요소의 속성을 추가하거나 수정하는 데 사용됩니다."
type: docs
weight: 2010
url: /ko/net/aspose.svg.builder/svgbuilderextensions/setattribute/
---
## SVGBuilderExtensions.SetAttribute<TBuilder> method

SVG 요소에 속성을 설정합니다. 이 메서드는 구축 중인 SVG 요소의 속성을 추가하거나 수정하는 데 사용됩니다.

```csharp
public static TBuilder SetAttribute<TBuilder>(this TBuilder builder, string name, string value)
    where TBuilder : IAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 속성이 설정되는 SVG 요소 빌더입니다. |
| 이름 | 설정할 속성의 이름입니다. |
| 값 | 속성의 값입니다. |

### 반환 값

메서드 체이닝을 위한 원본 SVG 요소 빌더입니다.

### 또 보기

* interface [IAttributeSetter](../../iattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
