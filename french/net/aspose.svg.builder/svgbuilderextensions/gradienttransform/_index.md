---
title: "SVGBuilderExtensions.GradientTransform"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode SVGBuilderExtensions GradientTransform. Définit l'attribut gradientTransform pour un élément gradient."
type: docs
weight: 980
url: /fr/net/aspose.svg.builder/svgbuilderextensions/gradienttransform/
---
## SVGBuilderExtensions.GradientTransform<TBuilder> method

Définit l'attribut 'gradientTransform' pour un élément de dégradé.

```csharp
public static TBuilder GradientTransform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'élément SVG auquel l'attribut est appliqué. |
| configurer | Une fonction pour configurer le constructeur de transformation SVG. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
