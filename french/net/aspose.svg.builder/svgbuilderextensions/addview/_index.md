---
title: "SVGBuilderExtensions.AddView"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode AddView de SVGBuilderExtensions. Ajoute une configuration d'élément view au constructeur"
type: docs
weight: 560
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addview/
---
## SVGBuilderExtensions.AddView<TBuilder> method

Ajoute une configuration d'élément 'view' au constructeur.

```csharp
public static TBuilder AddView<TBuilder>(this TBuilder builder, 
    Action<SVGViewElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'view'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGViewElementBuilder](../../svgviewelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
