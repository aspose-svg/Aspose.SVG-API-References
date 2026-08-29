---
title: "SVGFEColorMatrixElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGFEColorMatrixElementBuilder 클래스. SVG 필터에서 사용되는 SVG feColorMatrix 요소를 생성하기 위한 빌더 클래스"
type: docs
weight: 1200
url: /ko/net/aspose.svg.builder/svgfecolormatrixelementbuilder/
---
## SVGFEColorMatrixElementBuilder class

SVG 필터에서 사용되는 SVG 'feColorMatrix' 요소를 생성하기 위한 Builder 클래스입니다.

```csharp
public class SVGFEColorMatrixElementBuilder : SVGElementBuilder<SVGFEColorMatrixElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGFEColorMatrixElementBuilder](svgfecolormatrixelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfecolormatrixelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | feColorMatrix 요소에 스크립트 구성을 추가합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEColorMatrixElement](../../aspose.svg.filters/svgfecolormatrixelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [TypeAndValues](../../aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/)(*[ColorMatrixOperation](../colormatrixoperation/), params double[]*) | feColorMatrix 요소의 'type' 및 'values' 속성을 설정하여 색상 매트릭스 연산과 해당 매개변수를 지정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEColorMatrixElement](../../aspose.svg.filters/svgfecolormatrixelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
