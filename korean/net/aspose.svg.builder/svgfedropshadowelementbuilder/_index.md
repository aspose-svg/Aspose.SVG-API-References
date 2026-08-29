---
title: "SVGFEDropShadowElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGFEDropShadowElementBuilder 클래스. SVG 필터 내에서 드롭 섀도우 효과를 적용하기 위해 사용되는 SVG feDropShadow 요소를 생성하는 빌더 클래스입니다."
type: docs
weight: 1270
url: /ko/net/aspose.svg.builder/svgfedropshadowelementbuilder/
---
## SVGFEDropShadowElementBuilder class

드롭 섀도우 효과를 적용하기 위해 SVG 필터 내에서 사용되는 SVG 'feDropShadow' 요소를 생성하기 위한 Builder 클래스입니다.

```csharp
public class SVGFEDropShadowElementBuilder : SVGElementBuilder<SVGFEDropShadowElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGFEDropShadowElementBuilder](svgfedropshadowelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfedropshadowelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | feDropShadow 요소에 스크립트 구성을 추가합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEDropShadowElement](../../aspose.svg.filters/svgfedropshadowelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Dx](../../aspose.svg.builder/svgfedropshadowelementbuilder/dx/)(*double*) | 드롭 섀도우의 수평 오프셋('dx')을 설정합니다. |
| [Dy](../../aspose.svg.builder/svgfedropshadowelementbuilder/dy/)(*double*) | 드롭 섀도우의 수직 오프셋('dy')을 설정합니다. |
| [StdDeviation](../../aspose.svg.builder/svgfedropshadowelementbuilder/stddeviation/)(*double, double?*) | 드롭 섀도우의 블러 효과에 대한 표준 편차를 설정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEDropShadowElement](../../aspose.svg.filters/svgfedropshadowelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
