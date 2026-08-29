---
title: "SVGPatternElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGPatternElementBuilder 클래스. SVG 내 그래픽 요소를 채우는 데 사용되는 패턴을 정의하기 위해 SVG 패턴 요소를 구성하는 빌더 클래스입니다. 이 클래스는 패턴 요소에 특화된 다양한 속성을 설정하고 내용을 구축하는 메서드를 제공합니다."
type: docs
weight: 1540
url: /ko/net/aspose.svg.builder/svgpatternelementbuilder/
---
## SVGPatternElementBuilder class

SVG 'pattern' 요소를 구성하기 위한 Builder 클래스이며, SVG 내 그래픽 요소를 채우는 데 사용되는 패턴을 정의합니다. 이 클래스는 'pattern' 요소에 특화된 다양한 속성을 설정하고 해당 콘텐츠를 구축하는 메서드를 제공합니다.

```csharp
public class SVGPatternElementBuilder : SVGElementBuilder<SVGPatternElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, IRectAttributeSetter, 
    IViewBoxAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGPatternElementBuilder](svgpatternelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGPatternElement](../../aspose.svg/svgpatternelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgpatternelementbuilder/href/)(*string*) | SVG 'pattern' 요소의 'href' 속성을 설정하여 이 패턴이 속성을 상속받는 다른 패턴에 대한 참조를 지정합니다. |
| [PatternContentUnits](../../aspose.svg.builder/svgpatternelementbuilder/patterncontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | SVG 'pattern' 요소의 'patternContentUnits' 속성을 설정하여 패턴 내용의 좌표 시스템을 지정합니다. |
| [PatternTransform](../../aspose.svg.builder/svgpatternelementbuilder/patterntransform/)(*Func&lt;TransformBuilder, TransformBuilder&gt;*) | SVG 'pattern' 요소의 'patternTransform' 속성을 설정하여 패턴에 변환을 적용합니다. |
| [PatternUnits](../../aspose.svg.builder/svgpatternelementbuilder/patternunits/)(*[CoordinateUnits](../coordinateunits/)*) | SVG 'pattern' 요소의 'patternUnits' 속성을 설정하여 패턴의 x, y, width, height에 대한 좌표 시스템을 지정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGPatternElement](../../aspose.svg/svgpatternelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
