---
title: "Classe SVGElementBuilderT"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Classe Aspose.Svg.Builder.SVGElementBuilder1T. Représente une classe de base pour la création d'éléments SVG de type T."
type: docs
weight: 1160
url: /fr/net/aspose.svg.builder/svgelementbuilder-1/
---
## SVGElementBuilder<T> class

Représente une classe de base pour construire des éléments SVG de type *T*.

```csharp
public abstract class SVGElementBuilder<T> : ISVGElementBuilder
    where T : SVGElement
```

| Paramètre | Description |
| --- | --- |
| T | Le type d'élément SVG dont ce constructeur est responsable de la création. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } | Obtient la liste des configurations à appliquer à l'élément SVG. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) | Ajoute une configuration d'attribut à l'élément SVG. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Construit l'élément SVG et applique toutes les configurations à celui‑ci. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build_1)(*T*) | Applique des configurations à un élément SVG existant. |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) | Construit l'élément SVG en tant que SVGElement générique. |

### Voir aussi

* interface [ISVGElementBuilder](../isvgelementbuilder/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
