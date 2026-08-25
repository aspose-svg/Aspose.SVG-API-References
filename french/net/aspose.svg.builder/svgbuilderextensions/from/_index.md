---
title: "SVGBuilderExtensions.From"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode From de SVGBuilderExtensions. Définit l'attribut from spécifiant la valeur de départ de l'animation avec un type de longueur indiqué"
type: docs
weight: 960
url: /fr/net/aspose.svg.builder/svgbuilderextensions/from/
---
## SVGBuilderExtensions.From<TBuilder> method

Définit l'attribut 'from', définissant la valeur de départ de l'animation avec un type de longueur spécifié.

```csharp
public static TBuilder From<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| value | La valeur de départ de l'animation. |
| type | Le type de longueur pour la valeur 'from'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
