---
title: "SVGBuilderExtensions.KeySplines"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode KeySplines de SVGBuilderExtensions. Définit l'attribut keySplines spécifiant les points de contrôle pour le rythme de l'animation"
type: docs
weight: 1060
url: /fr/net/aspose.svg.builder/svgbuilderextensions/keysplines/
---
## SVGBuilderExtensions.KeySplines<TBuilder> method

Définit l'attribut 'keySplines', en spécifiant les points de contrôle du rythme de l'animation.

```csharp
public static TBuilder KeySplines<TBuilder>(this TBuilder builder, 
    Action<AnimationSplineBuilder> buildSplines)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| buildSplines | L'action pour construire la configuration du spline. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [AnimationSplineBuilder](../../animationsplinebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
