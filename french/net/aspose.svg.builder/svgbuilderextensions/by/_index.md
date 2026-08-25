---
title: "SVGBuilderExtensions.By"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode By de SVGBuilderExtensions. Définit l'attribut by qui spécifie la valeur de décalage relative pour l'animation avec un type de longueur spécifié"
type: docs
weight: 620
url: /fr/net/aspose.svg.builder/svgbuilderextensions/by/
---
## SVGBuilderExtensions.By<TBuilder> method

Définit l'attribut 'by', définissant la valeur de décalage relative pour l'animation avec un type de longueur spécifié.

```csharp
public static TBuilder By<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| value | La valeur de décalage relative pour l'animation. |
| type | Le type de longueur pour la valeur 'by'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
