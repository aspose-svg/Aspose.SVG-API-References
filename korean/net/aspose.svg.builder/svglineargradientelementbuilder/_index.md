---
title: "SVGLinearGradientElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGLinearGradientElementBuilder 클래스. SVG 그래픽 내에서 선형 그라디언트를 정의하는 SVG linearGradient 요소를 구성하기 위한 빌더 클래스. linearGradient 요소 내부의 콘텐츠를 구축하고 SVG의 linearGradient 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다."
type: docs
weight: 1490
url: /ko/net/aspose.svg.builder/svglineargradientelementbuilder/
---
## SVGLinearGradientElementBuilder class

SVG 'linearGradient' 요소를 구성하기 위한 Builder 클래스이며, SVG 그래픽 내에서 선형 그라디언트를 정의하는 데 사용됩니다. 'linearGradient' 요소 내부의 콘텐츠를 구축하고, SVG에서 'linearGradient' 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다.

```csharp
public class SVGLinearGradientElementBuilder : SVGElementBuilder<SVGLinearGradientElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, IGradientStopElementBuilder, 
    IPresentationAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGLinearGradientElementBuilder](svglineargradientelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svglineargradientelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | SVG 'linearGradient' 요소에 애니메이트 변환 구성을 추가합니다. |
| [AddScript](../../aspose.svg.builder/svglineargradientelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | SVG 'linearGradient' 요소에 스크립트 구성을 추가합니다. |
| [AddStyle](../../aspose.svg.builder/svglineargradientelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | SVG 'linearGradient' 요소에 스타일 구성을 추가합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGLinearGradientElement](../../aspose.svg/svglineargradientelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svglineargradientelementbuilder/href/)(*string*) | SVG 'linearGradient' 요소의 'href' 속성을 설정하여 다른 그라디언트를 참조하도록 지정합니다. |
| [X1](../../aspose.svg.builder/svglineargradientelementbuilder/x1/)(*double, [LengthType](../lengthtype/)*) | SVG 'linearGradient' 요소의 'x1' 속성을 설정하여 그라디언트 시작점의 x 좌표를 지정합니다. |
| [X2](../../aspose.svg.builder/svglineargradientelementbuilder/x2/)(*double, [LengthType](../lengthtype/)*) | SVG 'linearGradient' 요소의 'x2' 속성을 설정하여 그라디언트 끝점의 x 좌표를 지정합니다. |
| [Y1](../../aspose.svg.builder/svglineargradientelementbuilder/y1/)(*double, [LengthType](../lengthtype/)*) | SVG 'linearGradient' 요소의 'y1' 속성을 설정하여 그라디언트 시작점의 y 좌표를 지정합니다. |
| [Y2](../../aspose.svg.builder/svglineargradientelementbuilder/y2/)(*double, [LengthType](../lengthtype/)*) | SVG 'linearGradient' 요소의 'y2' 속성을 설정하여 그라디언트 끝점의 y 좌표를 지정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGLinearGradientElement](../../aspose.svg/svglineargradientelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IGradientStopElementBuilder](../igradientstopelementbuilder/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
