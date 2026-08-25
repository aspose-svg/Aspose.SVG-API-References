---
title: "SVGBuilderExtensions.Stroke"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode Stroke de SVGBuilderExtensions. Définit l'attribut stroke pour un élément SVG en utilisant une configuration de peinture personnalisée"
type: docs
weight: 2080
url: /fr/net/aspose.svg.builder/svgbuilderextensions/stroke/
---
## Stroke<TBuilder>(*this TBuilder, Action&lt;PaintBuilder&gt;*) {#stroke_1}

Définit l'attribut 'stroke' pour un élément SVG en utilisant une configuration de peinture personnalisée.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Action<PaintBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | Un délégué pour configurer la peinture. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [PaintBuilder](../../paintbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Stroke<TBuilder>(*this TBuilder, Color*) {#stroke_2}

Définit l'attribut 'stroke' pour un élément SVG en utilisant une couleur spécifique.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Color color)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| color | La couleur à utiliser pour le trait. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Stroke<TBuilder>(*this TBuilder, [Paint](../../paint/)*) {#stroke}

Définit l'attribut 'stroke' pour un élément SVG en utilisant une valeur de peinture prédéfinie.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Paint paint)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| paint | La valeur de peinture à définir. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* enum [Paint](../../paint/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
