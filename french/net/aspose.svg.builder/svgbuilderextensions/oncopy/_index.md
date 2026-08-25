---
title: "SVGBuilderExtensions.OnCopy"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode OnCopy de SVGBuilderExtensions. Définit l'attribut d'événement oncopy qui spécifie un script à exécuter lorsque le contenu est copié depuis l'élément SVG"
type: docs
weight: 1270
url: /fr/net/aspose.svg.builder/svgbuilderextensions/oncopy/
---
## SVGBuilderExtensions.OnCopy<TBuilder> method

Définit l'attribut d'événement 'oncopy', définissant un script à exécuter lorsque le contenu est copié depuis l'élément SVG.

```csharp
public static TBuilder OnCopy<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| value | La fonction JavaScript ou le script à exécuter lors de l'événement de copie. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
