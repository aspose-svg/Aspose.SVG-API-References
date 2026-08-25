---
title: "SVGBuilderExtensions.Rotate"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode Rotate de SVGBuilderExtensions. Définit les angles de rotation pour chaque caractère ou segment du contenu texte."
type: docs
weight: 2000
url: /fr/net/aspose.svg.builder/svgbuilderextensions/rotate/
---
## Rotate<TBuilder>(*this TBuilder, params double[]*) {#rotate_1}

Définit les angles de rotation pour les caractères individuels ou les segments du contenu texte.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| valeurs | Un tableau d'angles de rotation en degrés. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

## Remarques

Cette méthode définit l'attribut 'rotate' avec plusieurs valeurs, permettant une rotation individuelle de chaque caractère ou segment de texte.

### Voir aussi

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Rotate<TBuilder>(*this TBuilder, double*) {#rotate}

Définit un angle de rotation unique pour l'ensemble du contenu texte.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, double value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| value | L'angle de rotation en degrés. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

## Remarques

Cette méthode définit l'attribut 'rotate' avec une seule valeur, appliquant le même angle de rotation à tout le contenu texte.

### Voir aussi

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
