---
title: "SVGBuilderExtensions.Min"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode Min de SVGBuilderExtensions. Définit l'attribut min spécifiant la durée minimale de l'animation."
type: docs
weight: 1170
url: /fr/net/aspose.svg.builder/svgbuilderextensions/min/
---
## Min<TBuilder>(*this TBuilder, TimeSpan*) {#min_1}

Définit l'attribut 'min', en spécifiant la durée minimale de l'animation.

```csharp
public static TBuilder Min<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| duration | La durée minimale de l'animation. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Min<TBuilder>(*this TBuilder, [Media](../../media/)*) {#min}

Définit l'attribut 'min', en spécifiant la condition de durée minimale pour l'animation basée sur les médias.

```csharp
public static TBuilder Min<TBuilder>(this TBuilder builder, Media value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| value | La condition de durée minimale liée aux médias pour l'animation. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* enum [Media](../../media/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
