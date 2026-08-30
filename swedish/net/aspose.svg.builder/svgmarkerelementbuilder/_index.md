---
title: "SVGMarkerElementBuilder klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.SVGMarkerElementBuilder klass. Byggklass för att konstruera ett SVG marker-element som används för att definiera grafiska markörer såsom pilspetsar eller punkter som kan fästas på path-, line-, polyline- och polygon-element. Denna klass möjliggör byggandet av innehåll inom marker-elementet och tillhandahåller metoder för att ställa in olika attribut som är specifika för marker-elementet i SVG."
type: docs
weight: 1500
url: /sv/net/aspose.svg.builder/svgmarkerelementbuilder/
---
## SVGMarkerElementBuilder class

Builder-klass för att konstruera ett SVG 'marker'-element, som används för att definiera grafiska markörer, såsom pilspetsar eller punkter, som kan fästas på 'path', 'line', 'polyline' och 'polygon'-elementen. Denna klass möjliggör byggandet av innehåll inom 'marker'-elementet och tillhandahåller metoder för att ställa in olika attribut specifika för 'marker'-elementet i SVG.

```csharp
public class SVGMarkerElementBuilder : SVGElementBuilder<SVGMarkerElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, 
    IRefCoordinatesAttributeSetter, IViewBoxAttributeSetter
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGMarkerElementBuilder](svgmarkerelementbuilder/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMarkerElement](../../aspose.svg/svgmarkerelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MarkerHeight](../../aspose.svg.builder/svgmarkerelementbuilder/markerheight/)(*double, [LengthType](../lengthtype/)*) | Ställer in attributet 'markerHeight' för SVG 'marker'-elementet och specificerar höjden på markörens viewport. |
| [MarkerUnits](../../aspose.svg.builder/svgmarkerelementbuilder/markerunits/)(*[MarkerUnits](../markerunits/)*) | Ställer in attributet 'markerUnits' för SVG 'marker'-elementet och specificerar koordinatsystemet för markörens attribut. |
| [MarkerWidth](../../aspose.svg.builder/svgmarkerelementbuilder/markerwidth/)(*double, [LengthType](../lengthtype/)*) | Ställer in attributet 'markerWidth' för SVG 'marker'-elementet och specificerar bredden på markörens viewport. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient)(*[Orient](../orient/)*) | Ställer in attributet 'orient' för SVG 'marker'-elementet och specificerar markörens orientering. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient_1)(*double, [AngleUnits](../angleunits/)*) | Ställer in attributet 'orient' för SVG 'marker'-elementet och specificerar orienteringsvinkeln för markören. |

### Se även

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
