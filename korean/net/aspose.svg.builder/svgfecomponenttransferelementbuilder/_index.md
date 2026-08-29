---
title: "SVGFEComponentTransferElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGFEComponentTransferElementBuilder 클래스. SVG 필터에서 사용되는 SVG feComponentTransfer 요소를 생성하기 위한 빌더 클래스"
type: docs
weight: 1210
url: /ko/net/aspose.svg.builder/svgfecomponenttransferelementbuilder/
---
## SVGFEComponentTransferElementBuilder class

SVG 필터에서 사용되는 SVG 'feComponentTransfer' 요소를 생성하기 위한 Builder 클래스입니다.

```csharp
public class SVGFEComponentTransferElementBuilder : 
    SVGElementBuilder<SVGFEComponentTransferElement>, ICoreAttributeSetter, 
    IDescriptiveElementBuilder, IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGFEComponentTransferElementBuilder](svgfecomponenttransferelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | 구성된 컴포넌트 전송 함수를 사용하여 SVGFEComponentTransferElement를 빌드합니다. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEComponentTransferElement](../../aspose.svg.filters/svgfecomponenttransferelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [WithFeFuncA](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/withfefunca/)(*Action&lt;SVGFEFuncAElementBuilder&gt;*) | 알파 채널에 대한 'feFuncA' 컴포넌트 전송 함수를 구성합니다. |
| [WithFeFuncB](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/withfefuncb/)(*Action&lt;SVGFEFuncBElementBuilder&gt;*) | 파란색 채널에 대한 'feFuncB' 컴포넌트 전송 함수를 구성합니다. |
| [WithFeFuncG](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/withfefuncg/)(*Action&lt;SVGFEFuncGElementBuilder&gt;*) | 녹색 채널에 대한 'feFuncG' 컴포넌트 전송 함수를 구성합니다. |
| [WithFeFuncR](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/withfefuncr/)(*Action&lt;SVGFEFuncRElementBuilder&gt;*) | 빨간색 채널에 대한 'feFuncR' 컴포넌트 전송 함수를 구성합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEComponentTransferElement](../../aspose.svg.filters/svgfecomponenttransferelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
