---
title: "SVGMarkerElementBuilder Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.SVGMarkerElementBuilder Klasse. Builder-Klasse zum Erstellen eines SVG‑Marker‑Elements, das verwendet wird, um grafische Marker wie Pfeilspitzen oder Aufzählungszeichen zu definieren, die an Pfad‑, Linien‑, Polylinien‑ und Polygon‑Elementen angehängt werden können. Diese Klasse ermöglicht das Erstellen von Inhalt innerhalb des Marker‑Elements und bietet Methoden zum Festlegen verschiedener, für das Marker‑Element in SVG spezifischer Attribute."
type: docs
weight: 1500
url: /de/net/aspose.svg.builder/svgmarkerelementbuilder/
---
## SVGMarkerElementBuilder class

Builder-Klasse zum Erstellen eines SVG 'marker'-Elements, das verwendet wird, um grafische Marker wie Pfeilspitzen oder Aufzählungszeichen zu definieren, die an den 'path'-, 'line'-, 'polyline'- und 'polygon'-Elementen angehängt werden können. Diese Klasse ermöglicht das Erstellen von Inhalten innerhalb des 'marker'-Elements und bietet Methoden zum Festlegen verschiedener Attribute, die speziell für das 'marker'-Element in SVG gelten.

```csharp
public class SVGMarkerElementBuilder : SVGElementBuilder<SVGMarkerElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, 
    IRefCoordinatesAttributeSetter, IViewBoxAttributeSetter
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGMarkerElementBuilder](svgmarkerelementbuilder/)() | Der Standard‑Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMarkerElement](../../aspose.svg/svgmarkerelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MarkerHeight](../../aspose.svg.builder/svgmarkerelementbuilder/markerheight/)(*double, [LengthType](../lengthtype/)*) | Setzt das Attribut 'markerHeight' des SVG‑'marker'-Elements und gibt die Höhe des Viewports des Markers an. |
| [MarkerUnits](../../aspose.svg.builder/svgmarkerelementbuilder/markerunits/)(*[MarkerUnits](../markerunits/)*) | Setzt das Attribut 'markerUnits' des SVG‑'marker'-Elements und gibt das Koordinatensystem für die Attribute des Markers an. |
| [MarkerWidth](../../aspose.svg.builder/svgmarkerelementbuilder/markerwidth/)(*double, [LengthType](../lengthtype/)*) | Setzt das Attribut 'markerWidth' des SVG‑'marker'-Elements und gibt die Breite des Viewports des Markers an. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient)(*[Orient](../orient/)*) | Setzt das Attribut 'orient' des SVG‑'marker'-Elements und gibt die Ausrichtung des Markers an. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient_1)(*double, [AngleUnits](../angleunits/)*) | Setzt das Attribut 'orient' des SVG‑'marker'-Elements und gibt den Orientierungswinkel des Markers an. |

### Siehe auch

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
