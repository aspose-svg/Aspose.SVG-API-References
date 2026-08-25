---
title: "SVGBuilderExtensions.To"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode To de SVGBuilderExtensions. Définit l'attribut to qui spécifie la valeur finale de l'animation avec un type de longueur spécifié."
type: docs
weight: 2250
url: /fr/net/aspose.svg.builder/svgbuilderextensions/to/
---
## SVGBuilderExtensions.To<TBuilder> method

Définit l'attribut 'to', en définissant la valeur finale de l'animation avec un type de longueur spécifié.

```csharp
public static TBuilder To<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| value | La valeur finale de l'animation. |
| type | Le type de longueur pour la valeur 'to'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
