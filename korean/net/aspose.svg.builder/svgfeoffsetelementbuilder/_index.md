---
title: "SVGFEOffsetElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGFEOffsetElementBuilder 클래스. 입력 이미지에 오프셋 효과를 적용하는 데 사용되는 SVG feOffset 요소를 생성하기 위한 빌더 클래스"
type: docs
weight: 1380
url: /ko/net/aspose.svg.builder/svgfeoffsetelementbuilder/
---
## SVGFEOffsetElementBuilder class

입력 이미지에 오프셋 효과를 적용하는 데 사용되는 SVG 'feOffset' 요소를 생성하기 위한 Builder 클래스입니다.

```csharp
public class SVGFEOffsetElementBuilder : SVGElementBuilder<SVGFEOffsetElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGFEOffsetElementBuilder](svgfeoffsetelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfeoffsetelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | feOffset 요소에 스크립트 구성을 추가합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEOffsetElement](../../aspose.svg.filters/svgfeoffsetelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Dx](../../aspose.svg.builder/svgfeoffsetelementbuilder/dx/)(*double*) | feOffset 요소의 'dx' 속성을 설정하여 수평 오프셋을 지정합니다. |
| [Dy](../../aspose.svg.builder/svgfeoffsetelementbuilder/dy/)(*double*) | feOffset 요소의 'dy' 속성을 설정하여 수직 오프셋을 지정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEOffsetElement](../../aspose.svg.filters/svgfeoffsetelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
