---
title: "SVGBuilderExtensions.AddMetadata"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode SVGBuilderExtensions AddMetadata. Ajoute une configuration d'élément metadata au constructeur. L'élément metadata est utilisé pour ajouter des métadonnées au contenu SVG."
type: docs
weight: 390
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addmetadata/
---
## SVGBuilderExtensions.AddMetadata<TBuilder,TElement> method

Ajoute une configuration d'élément 'metadata' au constructeur. L'élément 'metadata' est utilisé pour ajouter des métadonnées au contenu SVG.

```csharp
public static TBuilder AddMetadata<TBuilder, TElement>(this TBuilder builder, 
    Action<SVGMetadataElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| TElement | Le type représentant l'élément 'metadata' dans le modèle SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'metadata'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGMetadataElementBuilder](../../svgmetadataelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
