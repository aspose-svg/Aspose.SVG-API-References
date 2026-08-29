---
title: "SVGTSpanElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGTSpanElementBuilder 클래스. SVG 문서 내에서 텍스트를 위치시키고 스타일링하는 데 사용되는 SVGTSpanElement를 생성하기 위한 빌더 클래스"
type: docs
weight: 1660
url: /ko/net/aspose.svg.builder/svgtspanelementbuilder/
---
## SVGTSpanElementBuilder class

SVGTSpanElement를 생성하기 위한 Builder 클래스이며, SVG 문서 내에서 텍스트의 위치 지정 및 스타일링에 사용됩니다.

```csharp
public class SVGTSpanElementBuilder : SVGElementBuilder<SVGTSpanElement>, 
    IBaseAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IPaintServerElementBuilder, ITextContentPositioningAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGTSpanElementBuilder](svgtspanelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddA](../../aspose.svg.builder/svgtspanelementbuilder/adda/)(*Action&lt;SVGAElementBuilder&gt;*) | 현재 tspan 요소에 앵커 (a) 요소를 추가합니다. |
| [AddScript](../../aspose.svg.builder/svgtspanelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | 현재 tspan 요소에 스크립트 요소를 추가합니다. |
| [AddStyle](../../aspose.svg.builder/svgtspanelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | 현재 tspan 요소에 스타일 요소를 추가합니다. |
| [AddTSpan](../../aspose.svg.builder/svgtspanelementbuilder/addtspan/)(*Action&lt;SVGTSpanElementBuilder&gt;*) | 현재 tspan 요소에 중첩된 tspan 요소를 추가합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGTSpanElement](../../aspose.svg/svgtspanelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGTSpanElement](../../aspose.svg/svgtspanelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../itextcontentpositioningattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
