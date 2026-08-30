---
title: "Clase SVGMarkerElementBuilder"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Clase Aspose.Svg.Builder.SVGMarkerElementBuilder. Clase constructora para crear un elemento marcador de SVG que se utiliza para definir marcadores gráficos como puntas de flecha o viñetas que pueden adjuntarse a los elementos de ruta, línea, polilínea y polígono. Esta clase permite la construcción de contenido dentro del elemento marcador y proporciona métodos para establecer varios atributos específicos del elemento marcador en SVG."
type: docs
weight: 1500
url: /es/net/aspose.svg.builder/svgmarkerelementbuilder/
---
## SVGMarkerElementBuilder class

Clase Builder para construir un elemento SVG 'marker', que se utiliza para definir marcadores gráficos, como puntas de flecha o viñetas, que pueden adjuntarse a los elementos 'path', 'line', 'polyline' y 'polygon'. Esta clase permite la creación de contenido dentro del elemento 'marker' y proporciona métodos para establecer varios atributos específicos del elemento 'marker' en SVG.

```csharp
public class SVGMarkerElementBuilder : SVGElementBuilder<SVGMarkerElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, 
    IRefCoordinatesAttributeSetter, IViewBoxAttributeSetter
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SVGMarkerElementBuilder](svgmarkerelementbuilder/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMarkerElement](../../aspose.svg/svgmarkerelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MarkerHeight](../../aspose.svg.builder/svgmarkerelementbuilder/markerheight/)(*double, [LengthType](../lengthtype/)*) | Establece el atributo 'markerHeight' del elemento 'marker' de SVG, especificando la altura del viewport del marcador. |
| [MarkerUnits](../../aspose.svg.builder/svgmarkerelementbuilder/markerunits/)(*[MarkerUnits](../markerunits/)*) | Establece el atributo 'markerUnits' del elemento 'marker' de SVG, especificando el sistema de coordenadas para los atributos del marcador. |
| [MarkerWidth](../../aspose.svg.builder/svgmarkerelementbuilder/markerwidth/)(*double, [LengthType](../lengthtype/)*) | Establece el atributo 'markerWidth' del elemento 'marker' de SVG, especificando el ancho del viewport del marcador. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient)(*[Orient](../orient/)*) | Establece el atributo 'orient' del elemento 'marker' de SVG, especificando la orientación del marcador. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient_1)(*double, [AngleUnits](../angleunits/)*) | Establece el atributo 'orient' del elemento 'marker' de SVG, especificando el ángulo de orientación del marcador. |

### Ver también

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
