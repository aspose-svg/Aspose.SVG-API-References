---
title: "SVGFEBlendElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGFEBlendElementBuilder 클래스. SVG 필터에서 사용되는 SVG feBlend 요소를 생성하기 위한 빌더 클래스"
type: docs
weight: 1190
url: /ko/net/aspose.svg.builder/svgfeblendelementbuilder/
---
## SVGFEBlendElementBuilder class

SVG 필터에서 사용되는 SVG 'feBlend' 요소를 생성하기 위한 Builder 클래스입니다.

```csharp
public class SVGFEBlendElementBuilder : SVGElementBuilder<SVGFEBlendElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGFEBlendElementBuilder](svgfeblendelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfeblendelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | feBlend 요소에 스크립트 구성을 추가합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEBlendElement](../../aspose.svg.filters/svgfeblendelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [In2](../../aspose.svg.builder/svgfeblendelementbuilder/in2/#in2)(*[FilterInput](../filterinput/)*) | feBlend 요소의 'in2' 속성을 설정하여 블렌딩 작업의 두 번째 입력을 지정합니다. |
| [In2](../../aspose.svg.builder/svgfeblendelementbuilder/in2/#in2_1)(*string*) | feBlend 요소의 'in2' 속성을 설정하여 블렌딩 작업의 두 번째 입력을 지정합니다. |
| [Mode](../../aspose.svg.builder/svgfeblendelementbuilder/mode/)(*[BlendMode](../blendmode/)*) | feBlend 요소의 'mode' 속성을 설정하여 사용할 블렌딩 모드를 지정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEBlendElement](../../aspose.svg.filters/svgfeblendelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
