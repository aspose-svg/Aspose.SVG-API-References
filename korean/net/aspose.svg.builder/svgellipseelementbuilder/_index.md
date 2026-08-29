---
title: "SVGEllipseElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGEllipseElementBuilder 클래스. SVG 그래픽 내에서 타원을 그리기 위해 사용되는 SVG ellipse 요소를 구성하기 위한 빌더 클래스입니다. 이 클래스는 ellipse 요소 내부의 콘텐츠를 구축할 수 있게 하며, SVG ellipse 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다."
type: docs
weight: 1170
url: /ko/net/aspose.svg.builder/svgellipseelementbuilder/
---
## SVGEllipseElementBuilder class

SVG 'ellipse' 요소를 구성하기 위한 Builder 클래스이며, 이 요소는 SVG 그래픽 내에서 타원을 그리는 데 사용됩니다. 'ellipse' 요소 내부의 콘텐츠 구축을 가능하게 하고, SVG에서 'ellipse' 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다.

```csharp
public class SVGEllipseElementBuilder : SVGElementBuilder<SVGEllipseElement>, 
    IAnimationElementBuilder, IDescriptiveElementBuilder, IPaintServerElementBuilder, 
    IShapeAttributeSetter, IShapeContentElementBuilder
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGEllipseElementBuilder](svgellipseelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGEllipseElement](../../aspose.svg/svgellipseelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Cx](../../aspose.svg.builder/svgellipseelementbuilder/cx/)(*double, [LengthType](../lengthtype/)*) | SVG 'ellipse' 요소의 'cx' 속성을 설정하여 타원의 중심 x좌표를 지정합니다. |
| [Cy](../../aspose.svg.builder/svgellipseelementbuilder/cy/)(*double, [LengthType](../lengthtype/)*) | SVG 'ellipse' 요소의 'cy' 속성을 설정하여 타원의 중심 y좌표를 지정합니다. |
| [Rx](../../aspose.svg.builder/svgellipseelementbuilder/rx/)(*double, [LengthType](../lengthtype/)*) | SVG 'ellipse' 요소의 'rx' 속성을 설정하여 타원의 수평 반경을 지정합니다. |
| [Ry](../../aspose.svg.builder/svgellipseelementbuilder/ry/)(*double, [LengthType](../lengthtype/)*) | SVG 'ellipse' 요소의 'ry' 속성을 설정하여 타원의 수직 반경을 지정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGEllipseElement](../../aspose.svg/svgellipseelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IShapeAttributeSetter](../ishapeattributesetter/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
