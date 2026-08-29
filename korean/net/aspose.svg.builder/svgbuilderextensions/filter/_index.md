---
title: "SVGBuilderExtensions.Filter"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Filter 메서드. 사용자 지정 구성을 사용하여 SVG 요소의 filter 속성을 설정합니다."
type: docs
weight: 840
url: /ko/net/aspose.svg.builder/svgbuilderextensions/filter/
---
## SVGBuilderExtensions.Filter<TBuilder> method

사용자 지정 구성으로 SVG 요소의 'filter' 속성을 설정합니다.

```csharp
public static TBuilder Filter<TBuilder>(this TBuilder builder, 
    Action<FilterValueListBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | FilterValueListBuilder를 구성하는 대리자입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [FilterValueListBuilder](../../filtervaluelistbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
