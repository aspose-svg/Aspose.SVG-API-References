---
title: "SVGLineElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGLineElementBuilder 클래스. SVG 그래픽 내에서 직선을 그리는 데 사용되는 SVG line 요소를 구성하기 위한 빌더 클래스. 이 클래스는 line 요소 내부의 콘텐츠를 구축하고 SVG line 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다."
type: docs
weight: 1480
url: /ko/net/aspose.svg.builder/svglineelementbuilder/
---
## SVGLineElementBuilder class

SVG 'line' 요소를 구성하기 위한 Builder 클래스이며, SVG 그래픽 내에서 직선을 그리는 데 사용됩니다. 이 클래스는 'line' 요소 내부의 콘텐츠를 구축하고, SVG에서 'line' 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다.

```csharp
public class SVGLineElementBuilder : SVGElementBuilder<SVGLineElement>, IAnimationElementBuilder, 
    IDescriptiveElementBuilder, IPaintServerElementBuilder, IShapeAttributeSetter, 
    IShapeContentElementBuilder
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGLineElementBuilder](svglineelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGLineElement](../../aspose.svg/svglineelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [X1](../../aspose.svg.builder/svglineelementbuilder/x1/)(*double, [LengthType](../lengthtype/)*) | SVG 'line' 요소의 'x1' 속성을 설정하여 선 시작점의 x좌표를 지정합니다. |
| [X2](../../aspose.svg.builder/svglineelementbuilder/x2/)(*double, [LengthType](../lengthtype/)*) | SVG 'line' 요소의 'x2' 속성을 설정하여 선 끝점의 x좌표를 지정합니다. |
| [Y1](../../aspose.svg.builder/svglineelementbuilder/y1/)(*double, [LengthType](../lengthtype/)*) | 'y1' 속성을 SVG 'line' 요소에 설정하여, 선의 시작점의 y 좌표를 지정합니다. |
| [Y2](../../aspose.svg.builder/svglineelementbuilder/y2/)(*double, [LengthType](../lengthtype/)*) | 'y2' 속성을 SVG 'line' 요소에 설정하여, 선의 끝점의 y 좌표를 지정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGLineElement](../../aspose.svg/svglineelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IShapeAttributeSetter](../ishapeattributesetter/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
