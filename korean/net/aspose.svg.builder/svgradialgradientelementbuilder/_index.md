---
title: "SVGRadialGradientElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGRadialGradientElementBuilder 클래스. SVG 그래픽 내에서 방사형 그라디언트를 정의하는 데 사용되는 SVG radialGradient 요소를 구성하기 위한 빌더 클래스입니다. 이 클래스는 radialGradient 요소 내부의 콘텐츠를 구축할 수 있게 하며, SVG에서 radialGradient 요소에 특정한 다양한 속성을 설정하는 메서드를 제공합니다."
type: docs
weight: 1570
url: /ko/net/aspose.svg.builder/svgradialgradientelementbuilder/
---
## SVGRadialGradientElementBuilder class

SVG 'radialGradient' 요소를 구성하기 위한 Builder 클래스이며, SVG 그래픽 내에서 방사형 그라디언트를 정의하는 데 사용됩니다. 이 클래스는 'radialGradient' 요소 내부의 콘텐츠를 구축하고, SVG에서 'radialGradient' 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다.

```csharp
public class SVGRadialGradientElementBuilder : SVGElementBuilder<SVGRadialGradientElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, IGradientStopElementBuilder, 
    IPresentationAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGRadialGradientElementBuilder](svgradialgradientelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svgradialgradientelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | SVG 'radialGradient' 요소에 애니메이트 변환 구성을 추가합니다. |
| [AddScript](../../aspose.svg.builder/svgradialgradientelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | SVG 'radialGradient' 요소에 스크립트 구성을 추가합니다. |
| [AddStyle](../../aspose.svg.builder/svgradialgradientelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | SVG 'radialGradient' 요소에 스타일 구성을 추가합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGRadialGradientElement](../../aspose.svg/svgradialgradientelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Cx](../../aspose.svg.builder/svgradialgradientelementbuilder/cx/)(*double, [LengthType](../lengthtype/)*) | SVG 'radialGradient' 요소의 'cx' 속성을 설정하여 그라디언트 중심의 x 좌표를 지정합니다. |
| [Cy](../../aspose.svg.builder/svgradialgradientelementbuilder/cy/)(*double, [LengthType](../lengthtype/)*) | SVG 'radialGradient' 요소의 'cy' 속성을 설정하여 그라디언트 중심의 y 좌표를 지정합니다. |
| [Fx](../../aspose.svg.builder/svgradialgradientelementbuilder/fx/)(*double, [LengthType](../lengthtype/)*) | SVG 'radialGradient' 요소의 'fx' 속성을 설정하여 그라디언트 초점의 x 좌표를 지정합니다. |
| [Fy](../../aspose.svg.builder/svgradialgradientelementbuilder/fy/)(*double, [LengthType](../lengthtype/)*) | SVG 'radialGradient' 요소의 'fy' 속성을 설정하여 그라디언트 초점의 y 좌표를 지정합니다. |
| [Href](../../aspose.svg.builder/svgradialgradientelementbuilder/href/)(*string*) | SVG 'radialGradient' 요소의 'href' 속성을 설정하여 다른 그라디언트를 참조하도록 지정합니다. |
| [R](../../aspose.svg.builder/svgradialgradientelementbuilder/r/)(*double, [LengthType](../lengthtype/)*) | SVG 'radialGradient' 요소의 'r' 속성을 설정하여 그라디언트의 반경을 지정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGRadialGradientElement](../../aspose.svg/svgradialgradientelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IGradientStopElementBuilder](../igradientstopelementbuilder/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
