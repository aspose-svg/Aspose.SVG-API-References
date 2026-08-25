---
title: "Classe SVGMaskElementBuilder"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Classe Aspose.Svg.Builder.SVGMaskElementBuilder. Classe de constructeur pour créer un élément de masque SVG utilisé pour définir un masque alpha afin de composer l'objet actuel dans l'arrière‑plan. Cette classe permet la création de contenu à l'intérieur de l'élément de masque et fournit des méthodes pour définir divers attributs spécifiques à l'élément de masque en SVG."
type: docs
weight: 1510
url: /fr/net/aspose.svg.builder/svgmaskelementbuilder/
---
## SVGMaskElementBuilder class

Classe Builder pour construire un élément SVG 'mask', qui est utilisé pour définir un masque alpha afin de composer l'objet actuel dans l'arrière-plan. Cette classe permet la création de contenu au sein de l'élément 'mask' et fournit des méthodes pour définir divers attributs spécifiques à l'élément 'mask' dans SVG.

```csharp
public class SVGMaskElementBuilder : SVGElementBuilder<SVGMaskElement>, ICompositeElementBuilder, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IRectAttributeSetter
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SVGMaskElementBuilder](svgmaskelementbuilder/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Méthodes

| Nom | Description |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMaskElement](../../aspose.svg/svgmaskelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MaskContentUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskcontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | Définit l'attribut 'maskContentUnits' de l'élément SVG 'mask', spécifiant le système de coordonnées pour le contenu du masque. |
| [MaskUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskunits/)(*[CoordinateUnits](../coordinateunits/)*) | Définit l'attribut 'maskUnits' de l'élément SVG 'mask', spécifiant le système de coordonnées pour les attributs du masque. |

### Voir aussi

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGMaskElement](../../aspose.svg/svgmaskelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
