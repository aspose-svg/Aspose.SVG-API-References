---
title: "SVGTextPathElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGTextPathElementBuilder 클래스. 텍스트를 경로에 맞추는 데 사용되는 SVG textPath 요소를 생성하기 위한 빌더 클래스"
type: docs
weight: 1680
url: /ko/net/aspose.svg.builder/svgtextpathelementbuilder/
---
## SVGTextPathElementBuilder class

SVG 'textPath' 요소를 생성하기 위한 Builder 클래스이며, 텍스트를 경로에 맞추는 데 사용됩니다.

```csharp
public class SVGTextPathElementBuilder : SVGElementBuilder<SVGTextPathElement>, 
    IBaseAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IPaintServerElementBuilder, IShapeContentElementBuilder, ITextContentSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGTextPathElementBuilder](svgtextpathelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddA](../../aspose.svg.builder/svgtextpathelementbuilder/adda/)(*Action&lt;SVGAElementBuilder&gt;*) | 'textPath'에 'a' (anchor) 요소 구성을 추가합니다. |
| [AddTSpan](../../aspose.svg.builder/svgtextpathelementbuilder/addtspan/)(*Action&lt;SVGTSpanElementBuilder&gt;*) | 'textPath'에 'tspan' 요소 구성을 추가합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGTextPathElement](../../aspose.svg/svgtextpathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgtextpathelementbuilder/href/)(*string*) | 'href' 속성을 설정하여, 경로 요소에 대한 참조를 지정합니다. |
| [LengthAdjust](../../aspose.svg.builder/svgtextpathelementbuilder/lengthadjust/)(*[LengthAdjust](../lengthadjust/)*) | 'lengthAdjust' 속성을 설정하여, 텍스트 길이 조정 방법을 지정합니다. |
| [Method](../../aspose.svg.builder/svgtextpathelementbuilder/method/)(*[TextPathMethod](../textpathmethod/)*) | 'method' 속성을 설정하여, 경로를 따라 텍스트 레이아웃 방식을 지정합니다. |
| [Path](../../aspose.svg.builder/svgtextpathelementbuilder/path/)(*Action&lt;PathBuilder&gt;*) | 텍스트용 경로를 구성합니다. |
| [Side](../../aspose.svg.builder/svgtextpathelementbuilder/side/)(*[HorizontalEdge](../horizontaledge/)*) | 'side' 속성을 설정하여, 텍스트가 경로의 어느 쪽에 배치될지 지정합니다. |
| [Spacing](../../aspose.svg.builder/svgtextpathelementbuilder/spacing/)(*[TextPathSpacing](../textpathspacing/)*) | 'spacing' 속성을 설정하여, 경로를 따라 텍스트의 간격 전략을 지정합니다. |
| [StartOffset](../../aspose.svg.builder/svgtextpathelementbuilder/startoffset/)(*double, [LengthType](../lengthtype/)*) | 'startOffset' 속성을 설정하여, 경로상의 텍스트 시작 위치를 지정합니다. |
| [TextLength](../../aspose.svg.builder/svgtextpathelementbuilder/textlength/)(*double, [LengthType](../lengthtype/)*) | 'textLength' 속성을 설정하여, 텍스트의 길이를 지정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGTextPathElement](../../aspose.svg/svgtextpathelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* interface [ITextContentSetter](../itextcontentsetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
