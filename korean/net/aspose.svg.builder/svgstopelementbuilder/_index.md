---
title: "SVGStopElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGStopElementBuilder 클래스. SVG stop 요소를 구성하기 위한 빌더 클래스입니다. stop 요소는 선형 또는 방사형 그라디언트 정의 내에서 색상 스톱을 정의하는 데 사용됩니다. 이 클래스는 offset 및 color와 같은 stop 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다."
type: docs
weight: 1620
url: /ko/net/aspose.svg.builder/svgstopelementbuilder/
---
## SVGStopElementBuilder class

SVG 'stop' 요소를 구성하기 위한 Builder 클래스이며, 'stop' 요소는 선형 또는 방사형 그라디언트 정의 내에서 색상 스톱을 정의하는 데 사용됩니다. 이 클래스는 offset 및 color와 같은 'stop' 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다.

```csharp
public class SVGStopElementBuilder : SVGElementBuilder<SVGStopElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGStopElementBuilder](svgstopelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgstopelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | SVG 'stop' 요소에 스크립트 구성을 추가합니다. |
| [AddStyle](../../aspose.svg.builder/svgstopelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | SVG 'stop' 요소에 스타일 구성을 추가합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStopElement](../../aspose.svg/svgstopelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Offset](../../aspose.svg.builder/svgstopelementbuilder/offset/)(*double, [StopUnitType](../stopunittype/)*) | 'offset' 속성을 SVG 'stop' 요소에 설정하여, 그라디언트 내에서 색상 스톱의 위치를 지정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStopElement](../../aspose.svg/svgstopelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
