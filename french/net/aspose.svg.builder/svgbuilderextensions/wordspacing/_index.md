---
title: "SVGBuilderExtensions.WordSpacing"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode WordSpacing de SVGBuilderExtensions. Définit l'attribut word-spacing pour un élément SVG spécifiant le comportement d'espacement entre les mots"
type: docs
weight: 2340
url: /fr/net/aspose.svg.builder/svgbuilderextensions/wordspacing/
---
## WordSpacing<TBuilder>(*this TBuilder, [Spacing](../../spacing/)*) {#wordspacing}

Définit l'attribut 'word-spacing' pour un élément SVG, en spécifiant le comportement d'espacement entre les mots.

```csharp
public static TBuilder WordSpacing<TBuilder>(this TBuilder builder, Spacing value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| value | La valeur d'espacement de mots prédéfinie. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* enum [Spacing](../../spacing/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## WordSpacing<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#wordspacing_1}

Définit l'attribut 'word-spacing' pour un élément SVG, en spécifiant le comportement d'espacement entre les mots avec une valeur personnalisée.

```csharp
public static TBuilder WordSpacing<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| value | La valeur d'espacement de mots. |
| type | Le type d'unité pour la valeur d'espacement. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
