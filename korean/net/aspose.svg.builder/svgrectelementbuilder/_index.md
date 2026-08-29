---
title: "SVGRectElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGRectElementBuilder 클래스. SVG rect 요소를 구성하기 위한 빌더 클래스입니다. rect 요소는 SVG 그래픽 내에서 사각형을 만들 때 사용됩니다. 이 클래스는 모서리 반경 및 크기와 같은 rect 요소 전용 다양한 속성을 설정하는 메서드를 제공합니다."
type: docs
weight: 1580
url: /ko/net/aspose.svg.builder/svgrectelementbuilder/
---
## SVGRectElementBuilder class

SVG 'rect' 요소를 구성하기 위한 Builder 클래스이며, 'rect' 요소는 SVG 그래픽 내에서 사각형을 만드는 데 사용됩니다. 이 클래스는 모서리 반경 및 크기를 포함한 'rect' 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다.

```csharp
public class SVGRectElementBuilder : SVGElementBuilder<SVGRectElement>, IAnimationElementBuilder, 
    IDescriptiveElementBuilder, IPaintServerElementBuilder, IRectAttributeSetter, 
    IShapeAttributeSetter, IShapeContentElementBuilder
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGRectElementBuilder](svgrectelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGRectElement](../../aspose.svg/svgrectelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Rx](../../aspose.svg.builder/svgrectelementbuilder/rx/)(*double, [LengthType](../lengthtype/)*) | SVG 'rect' 요소의 'rx' 속성을 설정하여 사각형 둥근 모서리의 가로 반경을 지정합니다. |
| [Ry](../../aspose.svg.builder/svgrectelementbuilder/ry/)(*double, [LengthType](../lengthtype/)*) | SVG 'rect' 요소의 'ry' 속성을 설정하여 사각형 둥근 모서리의 세로 반경을 지정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGRectElement](../../aspose.svg/svgrectelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IShapeAttributeSetter](../ishapeattributesetter/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
