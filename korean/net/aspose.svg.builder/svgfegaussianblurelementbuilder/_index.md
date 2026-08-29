---
title: "SVGFEGaussianBlurElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGFEGaussianBlurElementBuilder 클래스. 가우시안 블러 필터 효과를 적용하는 SVG feGaussianBlur 요소를 생성하기 위한 빌더 클래스"
type: docs
weight: 1330
url: /ko/net/aspose.svg.builder/svgfegaussianblurelementbuilder/
---
## SVGFEGaussianBlurElementBuilder class

가우시안 블러 필터 효과를 적용하는 SVG 'feGaussianBlur' 요소를 생성하기 위한 Builder 클래스입니다.

```csharp
public class SVGFEGaussianBlurElementBuilder : SVGElementBuilder<SVGFEGaussianBlurElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGFEGaussianBlurElementBuilder](svgfegaussianblurelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfegaussianblurelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | feGaussianBlur 요소에 스크립트 구성을 추가합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEGaussianBlurElement](../../aspose.svg.filters/svgfegaussianblurelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [StdDeviation](../../aspose.svg.builder/svgfegaussianblurelementbuilder/stddeviation/)(*double, double?*) | 가우시안 블러 효과의 표준 편차를 설정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEGaussianBlurElement](../../aspose.svg.filters/svgfegaussianblurelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
