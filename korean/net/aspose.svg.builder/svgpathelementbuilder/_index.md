---
title: "SVGPathElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGPathElementBuilder 클래스. SVG 문서에서 경로를 정의하는 데 사용되는 SVG path 요소를 구성하기 위한 빌더 클래스. 이 클래스는 path 요소에 특화된 다양한 속성을 설정하고 내용을 구축하는 메서드를 제공합니다."
type: docs
weight: 1530
url: /ko/net/aspose.svg.builder/svgpathelementbuilder/
---
## SVGPathElementBuilder class

SVG 'path' 요소를 구성하기 위한 Builder 클래스이며, SVG 문서에서 경로를 정의하는 데 사용됩니다. 이 클래스는 'path' 요소에 특화된 다양한 속성을 설정하고 해당 콘텐츠를 구축하는 메서드를 제공합니다.

```csharp
public class SVGPathElementBuilder : SVGElementBuilder<SVGPathElement>, IAnimationElementBuilder, 
    IDescriptiveElementBuilder, IPaintServerElementBuilder, IShapeAttributeSetter, 
    IShapeContentElementBuilder
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGPathElementBuilder](svgpathelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGPathElement](../../aspose.svg/svgpathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [D](../../aspose.svg.builder/svgpathelementbuilder/d/)(*Action&lt;PathBuilder&gt;*) | SVG 'path' 요소의 'd' 속성을 설정하여 경로의 형태를 정의합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGPathElement](../../aspose.svg/svgpathelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IShapeAttributeSetter](../ishapeattributesetter/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
