---
title: "SVGStopElementBuilder Classe"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Aspose.Svg.Builder.SVGStopElementBuilder class. Classe de constructeur pour créer un élément stop SVG. L'élément stop est utilisé dans une définition de dégradé, linéaire ou radial, pour définir les arrêts de couleur. Cette classe fournit des méthodes pour définir divers attributs spécifiques à l'élément stop tels que le décalage et la couleur."
type: docs
weight: 1620
url: /fr/net/aspose.svg.builder/svgstopelementbuilder/
---
## SVGStopElementBuilder class

Classe de constructeur pour créer un élément SVG 'stop'. L'élément 'stop' est utilisé dans une définition de dégradé (linéaire ou radial) pour définir les points d'arrêt de couleur. Cette classe fournit des méthodes pour définir divers attributs spécifiques à l'élément 'stop', tels que le décalage et la couleur.

```csharp
public class SVGStopElementBuilder : SVGElementBuilder<SVGStopElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SVGStopElementBuilder](svgstopelementbuilder/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgstopelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Ajoute une configuration de script à l'élément SVG 'stop'. |
| [AddStyle](../../aspose.svg.builder/svgstopelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Ajoute une configuration de style à l'élément SVG 'stop'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStopElement](../../aspose.svg/svgstopelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Offset](../../aspose.svg.builder/svgstopelementbuilder/offset/)(*double, [StopUnitType](../stopunittype/)*) | Définit l'attribut 'offset' de l'élément SVG 'stop', spécifiant la position de l'arrêt de couleur dans le dégradé. |

### Voir aussi

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStopElement](../../aspose.svg/svgstopelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
