---
title: "SVGBuilderExtensions.AddContent"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode AddContent de SVGBuilderExtensions. Ajoute du contenu texte à l'élément SVG."
type: docs
weight: 90
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addcontent/
---
## SVGBuilderExtensions.AddContent<TBuilder> method

Ajoute du contenu texte à l'élément SVG.

```csharp
public static TBuilder AddContent<TBuilder>(this TBuilder builder, string text)
    where TBuilder : ISVGElementBuilder, ITextContentSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| texte | Le texte à ajouter à l'élément. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

## Remarques

Cette méthode permet d'ajouter du contenu texte directement à un élément SVG. Elle est utile pour les éléments contenant des données textuelles.

### Voir aussi

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentSetter](../../itextcontentsetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
