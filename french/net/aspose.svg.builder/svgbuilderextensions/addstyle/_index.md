---
title: "SVGBuilderExtensions.AddStyle"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode SVGBuilderExtensions AddStyle. Ajoute une configuration d'élément style au constructeur"
type: docs
weight: 490
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addstyle/
---
## SVGBuilderExtensions.AddStyle<TBuilder> method

Ajoute une configuration d'élément 'style' au constructeur.

```csharp
public static TBuilder AddStyle<TBuilder>(this TBuilder builder, 
    Action<SVGStyleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'style'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGStyleElementBuilder](../../svgstyleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
