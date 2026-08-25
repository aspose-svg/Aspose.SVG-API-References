---
title: "SVGBuilderExtensions.Filter"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode Filter de SVGBuilderExtensions. Définit l'attribut filter pour un élément SVG en utilisant une configuration personnalisée"
type: docs
weight: 840
url: /fr/net/aspose.svg.builder/svgbuilderextensions/filter/
---
## SVGBuilderExtensions.Filter<TBuilder> method

Définit l'attribut 'filter' pour un élément SVG en utilisant une configuration personnalisée.

```csharp
public static TBuilder Filter<TBuilder>(this TBuilder builder, 
    Action<FilterValueListBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | Un délégué pour configurer le FilterValueListBuilder. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [FilterValueListBuilder](../../filtervaluelistbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
