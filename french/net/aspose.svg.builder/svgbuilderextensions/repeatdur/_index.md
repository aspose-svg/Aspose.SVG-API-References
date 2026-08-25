---
title: "SVGBuilderExtensions.RepeatDur"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode RepeatDur de SVGBuilderExtensions. Définit l'attribut repeatDur spécifiant la durée totale pendant laquelle l'animation doit se répéter"
type: docs
weight: 1960
url: /fr/net/aspose.svg.builder/svgbuilderextensions/repeatdur/
---
## RepeatDur<TBuilder>(*this TBuilder, TimeSpan*) {#repeatdur_1}

Définit l'attribut 'repeatDur', spécifiant la durée totale pendant laquelle l'animation doit se répéter.

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| duration | La durée totale pour répéter l'animation. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RepeatDur<TBuilder>(*this TBuilder, [IndefiniteRepeat](../../indefiniterepeat/)*) {#repeatdur}

Définit l'attribut 'repeatDur', spécifiant une durée totale indéfinie pour l'animation en utilisant une énumération prédéfinie.

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, IndefiniteRepeat value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| value | La durée totale indéfinie prédéfinie pour répéter l'animation. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* enum [IndefiniteRepeat](../../indefiniterepeat/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
