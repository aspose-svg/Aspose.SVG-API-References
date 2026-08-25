---
title: "Classe SVGImageElementBuilder"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Classe Aspose.Svg.Builder.SVGImageElementBuilder. Classe de construction pour créer un élément d'image SVG. Cet élément est utilisé pour intégrer des images dans les graphiques SVG. Elle fournit des méthodes pour définir divers attributs spécifiques à l'élément image et pour ajouter des configurations supplémentaires telles que des chemins de découpe, des masques, des styles et des scripts."
type: docs
weight: 1470
url: /fr/net/aspose.svg.builder/svgimageelementbuilder/
---
## SVGImageElementBuilder class

Classe Builder pour construire un élément SVG 'image'. Cet élément est utilisé pour intégrer des images dans les graphiques SVG. Il fournit des méthodes pour définir divers attributs spécifiques à l'élément 'image' et pour ajouter des configurations supplémentaires telles que des chemins de découpe, des masques, des styles et des scripts.

```csharp
public class SVGImageElementBuilder : SVGElementBuilder<SVGImageElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SVGImageElementBuilder](svgimageelementbuilder/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddClipPath](../../aspose.svg.builder/svgimageelementbuilder/addclippath/)(*Action&lt;SVGClipPathElementBuilder&gt;*) | Ajoute une configuration de chemin de découpe à l'élément SVG 'image'. |
| [AddMask](../../aspose.svg.builder/svgimageelementbuilder/addmask/)(*Action&lt;SVGMaskElementBuilder&gt;*) | Ajoute une configuration de masque à l'élément SVG 'image'. |
| [AddScript](../../aspose.svg.builder/svgimageelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Ajoute une configuration de script à l'élément SVG 'image'. |
| [AddStyle](../../aspose.svg.builder/svgimageelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Ajoute une configuration de style à l'élément SVG 'image'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGImageElement](../../aspose.svg/svgimageelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgimageelementbuilder/href/)(*string*) | Définit l'attribut 'href' de l'élément SVG 'image', en spécifiant l'URL de l'image à intégrer. |
| [HrefBase64FromBytes](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64frombytes/)(*byte[], string*) | Définit l'attribut 'href' de l'élément SVG 'image' en utilisant des octets d'image encodés en base64. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile)(*string*) | Définit l'attribut 'href' de l'élément SVG 'image' en utilisant un fichier image encodé en base64. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile_1)(*string, string*) | Définit l'attribut 'href' de l'élément SVG 'image' en utilisant un fichier image encodé en base64 avec un type MIME spécifié. |

### Voir aussi

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGImageElement](../../aspose.svg/svgimageelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
