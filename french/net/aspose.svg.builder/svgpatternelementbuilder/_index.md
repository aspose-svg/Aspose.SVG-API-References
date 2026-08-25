---
title: "Classe SVGPatternElementBuilder"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Aspose.Svg.Builder.SVGPatternElementBuilder class. Classe de constructeur pour créer un élément de motif SVG qui est utilisé pour définir un motif à utiliser pour remplir les éléments graphiques dans SVG. Cette classe fournit des méthodes pour définir divers attributs spécifiques à l'élément de motif et pour construire son contenu."
type: docs
weight: 1540
url: /fr/net/aspose.svg.builder/svgpatternelementbuilder/
---
## SVGPatternElementBuilder class

Classe Builder pour construire un élément SVG 'pattern', qui est utilisé pour définir un motif à utiliser pour remplir les éléments graphiques dans SVG. Cette classe fournit des méthodes pour définir divers attributs spécifiques à l'élément 'pattern' et pour créer son contenu.

```csharp
public class SVGPatternElementBuilder : SVGElementBuilder<SVGPatternElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, IRectAttributeSetter, 
    IViewBoxAttributeSetter
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SVGPatternElementBuilder](svgpatternelementbuilder/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Méthodes

| Nom | Description |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGPatternElement](../../aspose.svg/svgpatternelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgpatternelementbuilder/href/)(*string*) | Définit l'attribut 'href' de l'élément SVG 'pattern', en spécifiant une référence à un autre motif dont ce motif hérite des attributs. |
| [PatternContentUnits](../../aspose.svg.builder/svgpatternelementbuilder/patterncontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | Définit l'attribut 'patternContentUnits' de l'élément SVG 'pattern', en spécifiant le système de coordonnées pour le contenu du motif. |
| [PatternTransform](../../aspose.svg.builder/svgpatternelementbuilder/patterntransform/)(*Func&lt;TransformBuilder, TransformBuilder&gt;*) | Définit l'attribut 'patternTransform' de l'élément SVG 'pattern', en appliquant une transformation au motif. |
| [PatternUnits](../../aspose.svg.builder/svgpatternelementbuilder/patternunits/)(*[CoordinateUnits](../coordinateunits/)*) | Définit l'attribut 'patternUnits' de l'élément SVG 'pattern', en spécifiant le système de coordonnées pour les x, y, largeur et hauteur du motif. |

### Voir aussi

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGPatternElement](../../aspose.svg/svgpatternelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
