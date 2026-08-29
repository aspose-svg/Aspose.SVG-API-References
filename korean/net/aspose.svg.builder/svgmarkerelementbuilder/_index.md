---
title: "SVGMarkerElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGMarkerElementBuilder 클래스. 경로, 선, 폴리라인 및 폴리곤 요소에 부착할 수 있는 화살표 머리나 불릿과 같은 그래픽 마커를 정의하는 SVG 마커 요소를 구성하기 위한 빌더 클래스. 이 클래스는 마커 요소 내부의 콘텐츠를 구축하고 SVG에서 마커 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다."
type: docs
weight: 1500
url: /ko/net/aspose.svg.builder/svgmarkerelementbuilder/
---
## SVGMarkerElementBuilder class

SVG 'marker' 요소를 구성하기 위한 Builder 클래스이며, 'path', 'line', 'polyline', 'polygon' 요소에 부착할 수 있는 화살표 머리나 불릿과 같은 그래픽 마커를 정의하는 데 사용됩니다. 이 클래스는 'marker' 요소 내부의 콘텐츠를 구축하고, SVG에서 'marker' 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다.

```csharp
public class SVGMarkerElementBuilder : SVGElementBuilder<SVGMarkerElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, 
    IRefCoordinatesAttributeSetter, IViewBoxAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGMarkerElementBuilder](svgmarkerelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMarkerElement](../../aspose.svg/svgmarkerelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MarkerHeight](../../aspose.svg.builder/svgmarkerelementbuilder/markerheight/)(*double, [LengthType](../lengthtype/)*) | SVG 'marker' 요소의 'markerHeight' 속성을 설정하여 마커 뷰포트의 높이를 지정합니다. |
| [MarkerUnits](../../aspose.svg.builder/svgmarkerelementbuilder/markerunits/)(*[MarkerUnits](../markerunits/)*) | SVG 'marker' 요소의 'markerUnits' 속성을 설정하여 마커 속성의 좌표 시스템을 지정합니다. |
| [MarkerWidth](../../aspose.svg.builder/svgmarkerelementbuilder/markerwidth/)(*double, [LengthType](../lengthtype/)*) | SVG 'marker' 요소의 'markerWidth' 속성을 설정하여 마커 뷰포트의 너비를 지정합니다. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient)(*[Orient](../orient/)*) | SVG 'marker' 요소의 'orient' 속성을 설정하여 마커의 방향을 지정합니다. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient_1)(*double, [AngleUnits](../angleunits/)*) | SVG 'marker' 요소의 'orient' 속성을 설정하여 마커의 방향 각도를 지정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGMarkerElement](../../aspose.svg/svgmarkerelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRefCoordinatesAttributeSetter](../irefcoordinatesattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
