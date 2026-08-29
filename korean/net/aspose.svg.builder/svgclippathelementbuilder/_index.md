---
title: "SVGClipPathElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGClipPathElementBuilder 클래스. 클리핑 경로를 정의하는 데 사용되는 SVG clipPath 요소를 구성하기 위한 빌더 클래스입니다. clipPath 요소 내부의 콘텐츠를 구축할 수 있게 하며, SVG에서 clipPath 요소에 특정한 다양한 속성을 설정하는 메서드를 제공합니다."
type: docs
weight: 1130
url: /ko/net/aspose.svg.builder/svgclippathelementbuilder/
---
## SVGClipPathElementBuilder class

SVG 'clipPath' 요소를 구성하기 위한 빌더 클래스이며, 클리핑 경로를 정의하는 데 사용됩니다. 이 클래스는 'clipPath' 요소 내부의 콘텐츠를 구축하고 해당 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다.

```csharp
public class SVGClipPathElementBuilder : SVGElementBuilder<SVGClipPathElement>, 
    IAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IShapeElementBuilder
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGClipPathElementBuilder](svgclippathelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgclippathelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | clipPath 요소에 스크립트 요소를 추가합니다. |
| [AddText](../../aspose.svg.builder/svgclippathelementbuilder/addtext/)(*Action&lt;SVGTextElementBuilder&gt;*) | clipPath 요소에 텍스트 요소를 추가합니다. |
| [AddUse](../../aspose.svg.builder/svgclippathelementbuilder/adduse/)(*Action&lt;SVGUseElementBuilder&gt;*) | clipPath 요소에 'use' 요소를 추가합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGClipPathElement](../../aspose.svg/svgclippathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [ClipPathUnits](../../aspose.svg.builder/svgclippathelementbuilder/clippathunits/)(*[CoordinateUnits](../coordinateunits/)*) | SVG 'clipPath' 요소의 'clipPathUnits' 속성을 설정하여 클리핑 경로의 좌표 시스템을 지정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGClipPathElement](../../aspose.svg/svgclippathelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IShapeElementBuilder](../ishapeelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
