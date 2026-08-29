---
title: "SVGFEImageElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGFEImageElementBuilder 클래스. 다른 필터 기본 요소에서 사용할 이미지를 정의하는 SVG feImage 요소를 생성하기 위한 빌더 클래스"
type: docs
weight: 1340
url: /ko/net/aspose.svg.builder/svgfeimageelementbuilder/
---
## SVGFEImageElementBuilder class

다른 필터 프리미티브에서 사용할 이미지를 정의하는 SVG 'feImage' 요소를 생성하기 위한 Builder 클래스입니다.

```csharp
public class SVGFEImageElementBuilder : SVGElementBuilder<SVGFEImageElement>, 
    IAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveAttributeSetter, IPresentationAttributeSetter, 
    IPreserveAspectRatioAttributeSetter, IXLinkAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGFEImageElementBuilder](svgfeimageelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svgfeimageelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | feImage 요소에 애니메이트 변환 구성을 추가합니다. |
| [AddScript](../../aspose.svg.builder/svgfeimageelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | feImage 요소에 스크립트 구성을 추가합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEImageElement](../../aspose.svg.filters/svgfeimageelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgfeimageelementbuilder/href/)(*string*) | feImage 요소의 'href' 속성을 설정하여 사용할 이미지의 URL을 정의합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEImageElement](../../aspose.svg.filters/svgfeimageelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveAttributeSetter](../ifilterprimitiveattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IXLinkAttributeSetter](../ixlinkattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
