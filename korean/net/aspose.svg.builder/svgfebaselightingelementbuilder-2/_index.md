---
title: "SVGFEBaseLightingElementBuilderTElementTBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGFEBaseLightingElementBuilder2TElementTBuilder 클래스. SVG 필터 효과 조명 요소 빌더를 위한 추상 기본 클래스"
type: docs
weight: 1180
url: /ko/net/aspose.svg.builder/svgfebaselightingelementbuilder-2/
---
## SVGFEBaseLightingElementBuilder<TElement,TBuilder> class

SVG 필터 효과 조명 요소 빌더를 위한 추상 기본 클래스입니다.

```csharp
public abstract class SVGFEBaseLightingElementBuilder<TElement, TBuilder> : 
    SVGElementBuilder<TElement>, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
    where TElement : SVGElement
    where TBuilder : SVGFEBaseLightingElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TElement | 빌드 중인 SVG 요소의 유형입니다. |
| TBuilder | 빌더 자체의 유형입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | 요소에 스크립트 구성을 추가합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | SVG 요소를 빌드하고, 지정된 경우 조명 소스 구성을 적용합니다. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*TElement*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [WithFeDistantLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfedistantlight/)(*Action&lt;SVGFEDistantLightElementBuilder&gt;*) | 필터 효과를 위한 원거리 조명 소스를 구성합니다. |
| [WithFePointLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfepointlight/)(*Action&lt;SVGFEPointLightElementBuilder&gt;*) | 필터 효과를 위한 점광원(포인트 라이트)을 구성합니다. |
| [WithFeSpotLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfespotlight/)(*Action&lt;SVGFESpotLightElementBuilder&gt;*) | 필터 효과를 위한 스포트라이트(스팟 라이트)를 구성합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
