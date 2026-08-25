---
title: "Classe SVGClipPathElementBuilder"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Classe Aspose.Svg.Builder.SVGClipPathElementBuilder. Classe de construction pour créer un élément SVG clipPath utilisé pour définir un chemin de découpe. Elle permet de construire le contenu à l'intérieur de l'élément clipPath et fournit des méthodes pour définir divers attributs spécifiques à l'élément clipPath dans SVG."
type: docs
weight: 1130
url: /fr/net/aspose.svg.builder/svgclippathelementbuilder/
---
## SVGClipPathElementBuilder class

Classe Builder pour construire un élément SVG 'clipPath', qui est utilisé pour définir un chemin de découpe. Elle permet la construction de contenu à l'intérieur de l'élément 'clipPath' et fournit des méthodes pour définir divers attributs spécifiques à l'élément 'clipPath' en SVG.

```csharp
public class SVGClipPathElementBuilder : SVGElementBuilder<SVGClipPathElement>, 
    IAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IShapeElementBuilder
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SVGClipPathElementBuilder](svgclippathelementbuilder/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgclippathelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Ajoute un élément script à l'élément clipPath. |
| [AddText](../../aspose.svg.builder/svgclippathelementbuilder/addtext/)(*Action&lt;SVGTextElementBuilder&gt;*) | Ajoute un élément texte à l'élément clipPath. |
| [AddUse](../../aspose.svg.builder/svgclippathelementbuilder/adduse/)(*Action&lt;SVGUseElementBuilder&gt;*) | Ajoute un élément 'use' à l'élément clipPath. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGClipPathElement](../../aspose.svg/svgclippathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [ClipPathUnits](../../aspose.svg.builder/svgclippathelementbuilder/clippathunits/)(*[CoordinateUnits](../coordinateunits/)*) | Définit l'attribut 'clipPathUnits' de l'élément SVG 'clipPath', en spécifiant le système de coordonnées pour le chemin de découpe. |

### Voir aussi

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGClipPathElement](../../aspose.svg/svgclippathelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IShapeElementBuilder](../ishapeelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
