---
title: "SVGBuilderExtensions.LetterSpacing"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode SVGBuilderExtensions LetterSpacing. Définit l'attribut letter-spacing pour un élément SVG en utilisant une valeur numérique et un type de longueur spécifique"
type: docs
weight: 1100
url: /fr/net/aspose.svg.builder/svgbuilderextensions/letterspacing/
---
## LetterSpacing<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#letterspacing_1}

Définit l'attribut 'letter-spacing' pour un élément SVG en utilisant une valeur numérique et un type de longueur spécifique.

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| value | La valeur d'espacement des lettres à définir. |
| type | Le type de longueur (par ex., px, em). |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## LetterSpacing<TBuilder>(*this TBuilder, [Spacing](../../spacing/)*) {#letterspacing}

Définit l'attribut 'letter-spacing' pour un élément SVG en utilisant une valeur d'espacement prédéfinie.

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, Spacing value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| value | La valeur d'espacement prédéfinie à définir. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* enum [Spacing](../../spacing/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
