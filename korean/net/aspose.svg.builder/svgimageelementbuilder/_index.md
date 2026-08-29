---
title: "SVGImageElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGImageElementBuilder 클래스. SVG 이미지 요소를 구성하기 위한 빌더 클래스. 이 요소는 SVG 그래픽 내에 이미지를 삽입하는 데 사용됩니다. 이미지 요소에 특화된 다양한 속성을 설정하고 클립 경로, 마스크, 스타일 및 스크립트와 같은 추가 구성을 추가하는 메서드를 제공합니다."
type: docs
weight: 1470
url: /ko/net/aspose.svg.builder/svgimageelementbuilder/
---
## SVGImageElementBuilder class

SVG 'image' 요소를 구성하기 위한 Builder 클래스이며, 이 요소는 SVG 그래픽에 이미지를 삽입하는 데 사용됩니다. 'image' 요소에 특화된 다양한 속성을 설정하고 클립 경로, 마스크, 스타일, 스크립트와 같은 추가 구성을 추가하는 메서드를 제공합니다.

```csharp
public class SVGImageElementBuilder : SVGElementBuilder<SVGImageElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGImageElementBuilder](svgimageelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddClipPath](../../aspose.svg.builder/svgimageelementbuilder/addclippath/)(*Action&lt;SVGClipPathElementBuilder&gt;*) | SVG 'image' 요소에 클립 경로 구성을 추가합니다. |
| [AddMask](../../aspose.svg.builder/svgimageelementbuilder/addmask/)(*Action&lt;SVGMaskElementBuilder&gt;*) | SVG 'image' 요소에 마스크 구성을 추가합니다. |
| [AddScript](../../aspose.svg.builder/svgimageelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | SVG 'image' 요소에 스크립트 구성을 추가합니다. |
| [AddStyle](../../aspose.svg.builder/svgimageelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | SVG 'image' 요소에 스타일 구성을 추가합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGImageElement](../../aspose.svg/svgimageelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgimageelementbuilder/href/)(*string*) | SVG 'image' 요소의 'href' 속성을 설정하여 삽입될 이미지의 URL을 지정합니다. |
| [HrefBase64FromBytes](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64frombytes/)(*byte[], string*) | SVG 'image' 요소의 'href' 속성을 이미지의 base64 인코딩된 바이트를 사용하여 설정합니다. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile)(*string*) | SVG 'image' 요소의 'href' 속성을 base64 인코딩된 이미지 파일을 사용하여 설정합니다. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile_1)(*string, string*) | SVG 'image' 요소의 'href' 속성을 지정된 MIME 유형을 가진 base64 인코딩된 이미지 파일을 사용하여 설정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGImageElement](../../aspose.svg/svgimageelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
