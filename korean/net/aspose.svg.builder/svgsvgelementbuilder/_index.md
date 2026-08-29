---
title: "SVGSVGElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGSVGElementBuilder 클래스. SVG 문서의 루트 요소인 SVGSVGElement를 생성하기 위한 빌더 클래스"
type: docs
weight: 1590
url: /ko/net/aspose.svg.builder/svgsvgelementbuilder/
---
## SVGSVGElementBuilder class

SVG 문서의 루트 요소인 SVGSVGElement를 생성하기 위한 Builder 클래스입니다.

```csharp
public class SVGSVGElementBuilder : SVGElementBuilder<SVGSVGElement>, ICompositeAttributeSetter, 
    ICompositeElementBuilder, IDocumentEventAttributeSetter, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter, IViewBoxAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGSVGElementBuilder](svgsvgelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| [BaseProfile](../../aspose.svg.builder/svgsvgelementbuilder/baseprofile/)(*double*) | SVG 요소의 'baseProfile' 속성을 설정합니다. 이 속성은 전체 SVG 사양 중 문서에 적용되는 하위 집합을 나타냅니다. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGSVGElement](../../aspose.svg/svgsvgelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [ContentScriptType](../../aspose.svg.builder/svgsvgelementbuilder/contentscripttype/)(*string*) | SVG 요소의 'contentScriptType' 속성을 설정합니다. 이 속성은 SVG 문서 내용에 대한 기본 스크립팅 언어를 지정합니다. |
| [ContentStyleType](../../aspose.svg.builder/svgsvgelementbuilder/contentstyletype/)(*string*) | SVG 요소의 'contentStyleType' 속성을 설정합니다. 이 속성은 SVG 문서 내용에 대한 기본 스타일링 언어를 지정합니다. |
| [Version](../../aspose.svg.builder/svgsvgelementbuilder/version/)(*double*) | SVG 요소의 'version' 속성을 설정합니다. 이 속성은 문서가 따르는 SVG 사양 버전을 지정합니다. |
| [WithXlink](../../aspose.svg.builder/svgsvgelementbuilder/withxlink/)() | SVG 요소에 XLink 네임스페이스 선언을 추가합니다. 이는 'xlink:href'와 같은 XLink 속성을 사용하기 위해 필요합니다. |
| [ZoomAndPan](../../aspose.svg.builder/svgsvgelementbuilder/zoomandpan/)(*string*) | SVG 요소의 'zoomAndPan' 속성을 설정합니다. 이 속성은 SVG 콘텐츠를 확대 및 이동할 수 있는지를 제어합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGSVGElement](../../aspose.svg/svgsvgelement/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [IDocumentEventAttributeSetter](../idocumenteventattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
