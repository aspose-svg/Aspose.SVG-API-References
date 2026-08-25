---
title: "SVGBuilderExtensions.FillOpacity"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode FillOpacity de SVGBuilderExtensions. Définit l'attribut fill-opacity pour un élément SVG. La valeur doit être comprise entre 0.0 totalement transparent et 1.0 totalement opaque"
type: docs
weight: 820
url: /fr/net/aspose.svg.builder/svgbuilderextensions/fillopacity/
---
## SVGBuilderExtensions.FillOpacity<TBuilder> method

Définit l'attribut 'fill-opacity' pour un élément SVG. La valeur doit être comprise entre 0.0 (totalement transparent) et 1.0 (totalement opaque).

```csharp
public static TBuilder FillOpacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| opacity | La valeur d'opacité à définir. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Lancée si l'opacité n'est pas dans la plage valide. |

### Voir aussi

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
