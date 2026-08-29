---
title: "SVGBuilderExtensions.AddFeMerge"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddFeMerge 메서드. 빌더에 feMerge 요소 구성을 추가합니다. 이 요소는 필터 효과를 순차적으로가 아니라 동시에 적용할 수 있게 합니다."
type: docs
weight: 240
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addfemerge/
---
## SVGBuilderExtensions.AddFeMerge<TBuilder> method

빌더에 'feMerge' 요소 구성을 추가합니다. 이 요소는 필터 효과를 순차적으로가 아니라 동시에 적용할 수 있게 합니다.

```csharp
public static TBuilder AddFeMerge<TBuilder>(this TBuilder builder, 
    Action<SVGFEMergeElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'feMerge' 요소에 대한 구성 작업입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGFEMergeElementBuilder](../../svgfemergeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
