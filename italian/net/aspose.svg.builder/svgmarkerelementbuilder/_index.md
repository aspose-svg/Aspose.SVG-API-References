---
title: "Classe SVGMarkerElementBuilder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Aspose.Svg.Builder.SVGMarkerElementBuilder classe. Classe costruttore per creare un elemento SVG marker, che viene utilizzato per definire marcatori grafici come punte di freccia o pallini che possono essere collegati agli elementi path, line, polyline e polygon. Questa classe consente la costruzione del contenuto all'interno dell'elemento marker e fornisce metodi per impostare vari attributi specifici dell'elemento marker in SVG"
type: docs
weight: 1500
url: /it/net/aspose.svg.builder/svgmarkerelementbuilder/
---
## SVGMarkerElementBuilder class

Classe Builder per costruire un elemento SVG 'marker', che è usato per definire marcatori grafici, come punte di freccia o pallini, che possono essere collegati agli elementi 'path', 'line', 'polyline' e 'polygon'. Questa classe consente la costruzione del contenuto all'interno dell'elemento 'marker' e fornisce metodi per impostare vari attributi specifici dell'elemento 'marker' in SVG.

```csharp
public class SVGMarkerElementBuilder : SVGElementBuilder<SVGMarkerElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, 
    IRefCoordinatesAttributeSetter, IViewBoxAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGMarkerElementBuilder](svgmarkerelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMarkerElement](../../aspose.svg/svgmarkerelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MarkerHeight](../../aspose.svg.builder/svgmarkerelementbuilder/markerheight/)(*double, [LengthType](../lengthtype/)*) | Imposta l'attributo 'markerHeight' dell'elemento SVG 'marker', specificando l'altezza del viewport del marcatore. |
| [MarkerUnits](../../aspose.svg.builder/svgmarkerelementbuilder/markerunits/)(*[MarkerUnits](../markerunits/)*) | Imposta l'attributo 'markerUnits' dell'elemento SVG 'marker', specificando il sistema di coordinate per gli attributi del marcatore. |
| [MarkerWidth](../../aspose.svg.builder/svgmarkerelementbuilder/markerwidth/)(*double, [LengthType](../lengthtype/)*) | Imposta l'attributo 'markerWidth' dell'elemento SVG 'marker', specificando la larghezza del viewport del marcatore. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient)(*[Orient](../orient/)*) | Imposta l'attributo 'orient' dell'elemento SVG 'marker', specificando l'orientamento del marcatore. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient_1)(*double, [AngleUnits](../angleunits/)*) | Imposta l'attributo 'orient' dell'elemento SVG 'marker', specificando l'angolo di orientamento del marcatore. |

### Vedi anche

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
