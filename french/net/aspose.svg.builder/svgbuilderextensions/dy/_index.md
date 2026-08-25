---
title: "SVGBuilderExtensions.Dy"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode Dy de SVGBuilderExtensions. Définit plusieurs valeurs d'ajustement vertical pour le contenu texte"
type: docs
weight: 780
url: /fr/net/aspose.svg.builder/svgbuilderextensions/dy/
---
## Dy<TBuilder>(*this TBuilder, double[], [LengthType](../../lengthtype/)*) {#dy_1}

Définit plusieurs valeurs d'ajustement vertical pour le contenu texte.

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double[] values, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| valeurs | Le tableau des valeurs d'ajustement vertical. |
| type | Le type d'unité de longueur pour les valeurs. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

## Remarques

Cette méthode définit l'attribut 'dy' avec plusieurs valeurs, permettant des ajustements verticaux individuels pour chaque caractère ou segment de texte.

### Voir aussi

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dy<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dy}

Définit une valeur d'ajustement vertical unique pour le contenu texte.

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| value | La valeur d'ajustement vertical. |
| type | Le type d'unité de longueur pour la valeur. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

## Remarques

Cette méthode définit l'attribut 'dy' avec une seule valeur, ajustant la position verticale du contenu texte.

### Voir aussi

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
