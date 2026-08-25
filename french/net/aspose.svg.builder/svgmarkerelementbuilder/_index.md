---
title: "Classe SVGMarkerElementBuilder"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Classe Aspose.Svg.Builder.SVGMarkerElementBuilder. Classe de constructeur pour créer un élément SVG marker utilisé pour définir des marqueurs graphiques tels que des pointes de flèche ou des puces pouvant être attachés aux éléments chemin, ligne, polyligne et polygone. Cette classe permet la création de contenu à l'intérieur de l'élément marker et fournit des méthodes pour définir divers attributs spécifiques à l'élément marker dans SVG."
type: docs
weight: 1500
url: /fr/net/aspose.svg.builder/svgmarkerelementbuilder/
---
## SVGMarkerElementBuilder class

Classe Builder pour construire un élément SVG 'marker', qui est utilisé pour définir des marqueurs graphiques, tels que des pointes de flèche ou des puces, pouvant être attachés aux éléments 'path', 'line', 'polyline' et 'polygon'. Cette classe permet la création de contenu au sein de l'élément 'marker' et fournit des méthodes pour définir divers attributs spécifiques à l'élément 'marker' dans SVG.

```csharp
public class SVGMarkerElementBuilder : SVGElementBuilder<SVGMarkerElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, 
    IRefCoordinatesAttributeSetter, IViewBoxAttributeSetter
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SVGMarkerElementBuilder](svgmarkerelementbuilder/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Méthodes

| Nom | Description |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMarkerElement](../../aspose.svg/svgmarkerelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MarkerHeight](../../aspose.svg.builder/svgmarkerelementbuilder/markerheight/)(*double, [LengthType](../lengthtype/)*) | Définit l'attribut 'markerHeight' de l'élément SVG 'marker', en spécifiant la hauteur du viewport du marqueur. |
| [MarkerUnits](../../aspose.svg.builder/svgmarkerelementbuilder/markerunits/)(*[MarkerUnits](../markerunits/)*) | Définit l'attribut 'markerUnits' de l'élément SVG 'marker', en spécifiant le système de coordonnées pour les attributs du marqueur. |
| [MarkerWidth](../../aspose.svg.builder/svgmarkerelementbuilder/markerwidth/)(*double, [LengthType](../lengthtype/)*) | Définit l'attribut 'markerWidth' de l'élément SVG 'marker', en spécifiant la largeur du viewport du marqueur. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient)(*[Orient](../orient/)*) | Définit l'attribut 'orient' de l'élément SVG 'marker', en spécifiant l'orientation du marqueur. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient_1)(*double, [AngleUnits](../angleunits/)*) | Définit l'attribut 'orient' de l'élément SVG 'marker', en spécifiant l'angle d'orientation du marqueur. |

### Voir aussi

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
