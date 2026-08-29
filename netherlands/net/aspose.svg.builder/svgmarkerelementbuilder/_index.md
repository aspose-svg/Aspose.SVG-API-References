---
title: "SVGMarkerElementBuilder Class"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.SVGMarkerElementBuilder class. Builderklasse voor het construeren van een SVG marker-element dat wordt gebruikt om grafische markers, zoals pijlpuntjes of opsommingstekens, te definiëren die kunnen worden gekoppeld aan pad-, lijn-, polyline- en polygon-elementen. Deze klasse maakt het mogelijk om inhoud binnen het marker-element te bouwen en biedt methoden om verschillende attributen die specifiek zijn voor het marker-element in SVG in te stellen."
type: docs
weight: 1500
url: /nl/net/aspose.svg.builder/svgmarkerelementbuilder/
---
## SVGMarkerElementBuilder class

Builder-klasse voor het construeren van een SVG 'marker'-element, dat wordt gebruikt om grafische markeringen, zoals pijlpuntjes of opsommingstekens, te definiëren die aan de 'path'-, 'line'-, 'polyline'- en 'polygon'-elementen kunnen worden gekoppeld. Deze klasse maakt het mogelijk om inhoud binnen het 'marker'-element op te bouwen en biedt methoden om verschillende attributen specifiek voor het 'marker'-element in SVG in te stellen.

```csharp
public class SVGMarkerElementBuilder : SVGElementBuilder<SVGMarkerElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, 
    IRefCoordinatesAttributeSetter, IViewBoxAttributeSetter
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SVGMarkerElementBuilder](svgmarkerelementbuilder/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMarkerElement](../../aspose.svg/svgmarkerelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MarkerHeight](../../aspose.svg.builder/svgmarkerelementbuilder/markerheight/)(*double, [LengthType](../lengthtype/)*) | Stelt het 'markerHeight' attribuut van het SVG 'marker' element in, waarbij de hoogte van de viewport van de marker wordt gespecificeerd. |
| [MarkerUnits](../../aspose.svg.builder/svgmarkerelementbuilder/markerunits/)(*[MarkerUnits](../markerunits/)*) | Stelt het 'markerUnits' attribuut van het SVG 'marker' element in, waarbij het coördinatensysteem voor de attributen van de marker wordt gespecificeerd. |
| [MarkerWidth](../../aspose.svg.builder/svgmarkerelementbuilder/markerwidth/)(*double, [LengthType](../lengthtype/)*) | Stelt het 'markerWidth' attribuut van het SVG 'marker' element in, waarbij de breedte van de viewport van de marker wordt gespecificeerd. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient)(*[Orient](../orient/)*) | Stelt het 'orient' attribuut van het SVG 'marker' element in, waarbij de oriëntatie van de marker wordt gespecificeerd. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient_1)(*double, [AngleUnits](../angleunits/)*) | Stelt het 'orient' attribuut van het SVG 'marker' element in, waarbij de oriëntatiehoek van de marker wordt gespecificeerd. |

### Zie ook

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
