---
title: "SVGBuilderExtensions.Y"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode Y de SVGBuilderExtensions. Définit l'attribut y pour un élément SVG"
type: docs
weight: 2400
url: /fr/net/aspose.svg.builder/svgbuilderextensions/y/
---
## Y<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#y_1}

Définit l'attribut 'y' pour un élément SVG.

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IYAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| value | La valeur de l'attribut 'y'. |
| type | Le type de mesure de longueur (la valeur par défaut est pixels). |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IYAttributeSetter](../../iyattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Y<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#y}

Définit l'attribut 'y' pour positionner le contenu texte le long de l'axe y.

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| type | Le type d'unité de longueur pour les valeurs. |
| valeurs | Les valeurs de position sur l'axe y. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

## Remarques

Cette méthode définit l'attribut 'y', qui détermine la ou les positions verticales de l'élément texte.

### Voir aussi

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
