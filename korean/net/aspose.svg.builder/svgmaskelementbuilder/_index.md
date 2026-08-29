---
title: "SVGMaskElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGMaskElementBuilder 클래스. 현재 객체를 배경에 합성하기 위한 알파 마스크를 정의하는 데 사용되는 SVG 마스크 요소를 구성하기 위한 빌더 클래스입니다. 이 클래스는 마스크 요소 내의 콘텐츠 구축을 가능하게 하며 SVG에서 마스크 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다."
type: docs
weight: 1510
url: /ko/net/aspose.svg.builder/svgmaskelementbuilder/
---
## SVGMaskElementBuilder class

SVG 'mask' 요소를 구성하기 위한 Builder 클래스이며, 현재 객체를 배경에 합성하기 위한 알파 마스크를 정의하는 데 사용됩니다. 이 클래스는 'mask' 요소 내부의 콘텐츠를 구축하고, SVG에서 'mask' 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다.

```csharp
public class SVGMaskElementBuilder : SVGElementBuilder<SVGMaskElement>, ICompositeElementBuilder, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IRectAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGMaskElementBuilder](svgmaskelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMaskElement](../../aspose.svg/svgmaskelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MaskContentUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskcontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | SVG 'mask' 요소의 'maskContentUnits' 속성을 설정하여 마스크 내용의 좌표 시스템을 지정합니다. |
| [MaskUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskunits/)(*[CoordinateUnits](../coordinateunits/)*) | SVG 'mask' 요소의 'maskUnits' 속성을 설정하여 마스크 속성의 좌표 시스템을 지정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGMaskElement](../../aspose.svg/svgmaskelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
