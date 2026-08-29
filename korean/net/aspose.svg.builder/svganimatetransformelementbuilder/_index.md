---
title: "SVGAnimateTransformElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGAnimateTransformElementBuilder 클래스. SVG 그래픽 내에서 변환 애니메이션을 만들기 위해 사용되는 SVG animateTransform 요소를 구성하기 위한 빌더 클래스입니다. animateTransform 요소 내부의 콘텐츠 구성을 가능하게 하며, SVG에서 animateTransform 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다."
type: docs
weight: 1100
url: /ko/net/aspose.svg.builder/svganimatetransformelementbuilder/
---
## SVGAnimateTransformElementBuilder class

SVG 'animateTransform' 요소를 구성하기 위한 빌더 클래스이며, SVG 그래픽 내에서 변환 애니메이션을 생성하는 데 사용됩니다. 이 클래스는 'animateTransform' 요소 내부의 콘텐츠를 구축하고 해당 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다.

```csharp
public class SVGAnimateTransformElementBuilder : SVGElementBuilder<SVGAnimateTransformElement>, 
    IAnimationAdditionAttributeSetter, IAnimationEventAttributeSetter, 
    IAnimationTargetAttributeSetter, IAnimationTargetElementAttributeSetter, 
    IAnimationTimingAttributeSetter, IAnimationValueAttributeSetter, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGAnimateTransformElementBuilder](svganimatetransformelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGAnimateTransformElement](../../aspose.svg/svganimatetransformelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Type](../../aspose.svg.builder/svganimatetransformelementbuilder/type/)(*[TransformationType](../transformationtype/)*) | SVG 'animateTransform' 요소의 'type' 속성을 설정하여 변환 유형을 지정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGAnimateTransformElement](../../aspose.svg/svganimatetransformelement/)
* interface [IAnimationAdditionAttributeSetter](../ianimationadditionattributesetter/)
* interface [IAnimationEventAttributeSetter](../ianimationeventattributesetter/)
* interface [IAnimationTargetAttributeSetter](../ianimationtargetattributesetter/)
* interface [IAnimationTargetElementAttributeSetter](../ianimationtargetelementattributesetter/)
* interface [IAnimationTimingAttributeSetter](../ianimationtimingattributesetter/)
* interface [IAnimationValueAttributeSetter](../ianimationvalueattributesetter/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
