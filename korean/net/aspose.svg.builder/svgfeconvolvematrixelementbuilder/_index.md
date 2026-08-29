---
title: "SVGFEConvolveMatrixElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGFEConvolveMatrixElementBuilder 클래스. 컨볼루션 매트릭스 효과를 적용하기 위해 SVG 필터에서 사용되는 SVG feConvolveMatrix 요소를 생성하는 빌더 클래스"
type: docs
weight: 1230
url: /ko/net/aspose.svg.builder/svgfeconvolvematrixelementbuilder/
---
## SVGFEConvolveMatrixElementBuilder class

컨볼루션 매트릭스 효과를 적용하기 위해 SVG 필터에서 사용되는 SVG 'feConvolveMatrix' 요소를 생성하기 위한 Builder 클래스입니다.

```csharp
public class SVGFEConvolveMatrixElementBuilder : SVGElementBuilder<SVGFEConvolveMatrixElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGFEConvolveMatrixElementBuilder](svgfeconvolvematrixelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | 요소에 스크립트 구성을 추가합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| [Bias](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/bias/)(*double*) | feConvolveMatrix 요소의 'bias' 속성을 설정합니다. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEConvolveMatrixElement](../../aspose.svg.filters/svgfeconvolvematrixelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Divisor](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/divisor/)(*double*) | feConvolveMatrix 요소의 'divisor' 속성을 설정합니다. |
| [EdgeMode](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/edgemode/)(*[EdgeMode](../edgemode/)*) | feConvolveMatrix 요소의 'edgeMode' 속성을 설정합니다. |
| [KernelMatrix](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/kernelmatrix/)(*params double[]*) | feConvolveMatrix 요소의 'kernelMatrix' 속성을 설정합니다. |
| [KernelUnitLength](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/kernelunitlength/)(*double, double?*) | feConvolveMatrix 요소의 'kernelUnitLength' 속성을 설정합니다. |
| [Order](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/order/)(*int, int?*) | feConvolveMatrix 요소의 'order' 속성을 설정합니다. |
| [PreserveAlpha](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/preservealpha/)(*bool*) | feConvolveMatrix 요소의 'preserveAlpha' 속성을 설정합니다. |
| [TargetX](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/targetx/)(*int*) | feConvolveMatrix 요소의 'targetX' 속성을 설정합니다. |
| [TargetY](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/targety/)(*int*) | feConvolveMatrix 요소의 'targetY' 속성을 설정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEConvolveMatrixElement](../../aspose.svg.filters/svgfeconvolvematrixelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
