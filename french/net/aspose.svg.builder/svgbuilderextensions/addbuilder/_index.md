---
title: "SVGBuilderExtensions.AddBuilder"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode SVGBuilderExtensions AddBuilder. Ajoute un constructeur d'élément SVG existant au constructeur d'élément SVG actuel. Cette méthode est utilisée pour inclure un constructeur d'élément SVG prédéfini dans le constructeur actuel."
type: docs
weight: 60
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addbuilder/
---
## SVGBuilderExtensions.AddBuilder<TBuilder,TElementBuilder> method

Ajoute un constructeur d'élément SVG existant au constructeur d'élément SVG actuel. Cette méthode est utilisée pour inclure un constructeur d'élément SVG prédéfini dans le constructeur actuel.

```csharp
public static TBuilder AddBuilder<TBuilder, TElementBuilder>(this TBuilder builder, 
    TElementBuilder elementBuilder)
    where TBuilder : ISVGElementBuilder
    where TElementBuilder : ISVGElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| TElementBuilder | Le type du constructeur d'élément SVG à configurer. TElementBuilder doit implémenter ISVGElementBuilder. |
| constructeur | Le constructeur d'élément SVG auquel l'autre constructeur d'élément est ajouté. |
| elementBuilder | Le constructeur d'élément SVG à ajouter. |

### Valeur de retour

Le constructeur d'élément SVG original pour l'enchaînement de méthodes.

### Voir aussi

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
