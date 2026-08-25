---
title: "SVGStyleElementBuilder Class"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Aspose.Svg.Builder.SVGStyleElementBuilder class. Une classe de construction pour créer un élément de style SVG. Cette classe facilite la création et la configuration d'un élément de style SVG avec des règles CSS"
type: docs
weight: 1630
url: /fr/net/aspose.svg.builder/svgstyleelementbuilder/
---
## SVGStyleElementBuilder class

Classe de constructeur pour créer un élément SVG 'style'. Cette classe facilite la création et la configuration d'un élément de style SVG avec des règles CSS.

```csharp
public class SVGStyleElementBuilder : SVGElementBuilder<SVGStyleElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SVGStyleElementBuilder](svgstyleelementbuilder/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddComment](../../aspose.svg.builder/svgstyleelementbuilder/addcomment/)(*string*) | Ajoute un commentaire au contenu du style. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule)(*string, Action&lt;RuleBuilder&gt;*) | Ajoute une règle CSS à l'élément de style en utilisant un RuleBuilder. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule_1)(*string, string*) | Ajoute une règle CSS à l'élément de style. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgstyleelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Construit l'élément de style SVG avec les règles CSS accumulées et l'ajoute au document spécifié. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStyleElement](../../aspose.svg/svgstyleelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Media](../../aspose.svg.builder/svgstyleelementbuilder/media/)(*string*) | Définit l'attribut 'media' de l'élément SVG 'style'. Cet attribut spécifie le média pour lequel les styles sont destinés, permettant aux styles d'être conditionnels en fonction du type de média. |
| [Title](../../aspose.svg.builder/svgstyleelementbuilder/title/)(*string*) | Définit l'attribut 'title' de l'élément SVG 'style'. Cet attribut fournit un titre indicatif pour l'élément de style, ce qui peut être utile pour l'accessibilité et le texte d'infobulle. |
| [Type](../../aspose.svg.builder/svgstyleelementbuilder/type/)(*string*) | Définit l'attribut 'type' de l'élément SVG 'style'. Cet attribut spécifie le langage de la feuille de style du contenu de l'élément. |

### Voir aussi

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStyleElement](../../aspose.svg/svgstyleelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
