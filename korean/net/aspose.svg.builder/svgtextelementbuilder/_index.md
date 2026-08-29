---
title: "SVGTextElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGTextElementBuilder 클래스. SVG 문서에서 텍스트를 정의하는 데 사용되는 SVGTextElement를 생성하기 위한 빌더 클래스"
type: docs
weight: 1670
url: /ko/net/aspose.svg.builder/svgtextelementbuilder/
---
## SVGTextElementBuilder class

SVGTextElement를 생성하기 위한 Builder 클래스이며, SVG 문서에서 텍스트를 정의하는 데 사용됩니다.

```csharp
public class SVGTextElementBuilder : SVGElementBuilder<SVGTextElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPaintServerElementBuilder, 
    IShapeContentElementBuilder, ITextContentPositioningAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGTextElementBuilder](svgtextelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddA](../../aspose.svg.builder/svgtextelementbuilder/adda/)(*Action&lt;SVGAElementBuilder&gt;*) | 텍스트 요소에 'a'(앵커) 요소를 추가하여 텍스트의 일부에 하이퍼링크를 적용할 수 있게 합니다. |
| [AddTextPath](../../aspose.svg.builder/svgtextelementbuilder/addtextpath/)(*Action&lt;SVGTextPathElementBuilder&gt;*) | 텍스트 요소에 'textPath' 요소를 추가하여 텍스트가 정의된 경로를 따라 표시되도록 합니다. |
| [AddTSpan](../../aspose.svg.builder/svgtextelementbuilder/addtspan/)(*Action&lt;SVGTSpanElementBuilder&gt;*) | 텍스트 요소에 'tspan' 요소를 추가하여 텍스트의 개별 섹션을 세밀하게 제어할 수 있게 합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGTextElement](../../aspose.svg/svgtextelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGTextElement](../../aspose.svg/svgtextelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../itextcontentpositioningattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
