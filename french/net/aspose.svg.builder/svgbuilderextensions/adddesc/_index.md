---
title: "SVGBuilderExtensions.AddDesc"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode AddDesc de SVGBuilderExtensions. Ajoute une configuration d'élément desc au constructeur. L'élément desc est utilisé pour fournir une description du contenu SVG."
type: docs
weight: 110
url: /fr/net/aspose.svg.builder/svgbuilderextensions/adddesc/
---
## SVGBuilderExtensions.AddDesc<TBuilder> method

Ajoute une configuration d'élément 'desc' au constructeur. L'élément 'desc' est utilisé pour fournir une description du contenu SVG.

```csharp
public static TBuilder AddDesc<TBuilder>(this TBuilder builder, 
    Action<SVGDescElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'desc'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGDescElementBuilder](../../svgdescelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
