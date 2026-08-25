---
title: "SVGBuilderExtensions.StrokeDashArray"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode StrokeDashArray de SVGBuilderExtensions. Définit l'attribut stroke-dasharray pour un élément SVG définissant le motif de tirets et d'espaces utilisé pour peindre le trait"
type: docs
weight: 2090
url: /fr/net/aspose.svg.builder/svgbuilderextensions/strokedasharray/
---
## StrokeDashArray<TBuilder>(*this TBuilder, params double[]*) {#strokedasharray_1}

Définit l'attribut 'stroke-dasharray' pour un élément SVG, définissant le motif de tirets et d'espaces utilisé pour peindre le contour.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, params double[] dashArray)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| dashArray | Le tableau des longueurs de tirets. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## StrokeDashArray<TBuilder>(*this TBuilder, [Dash](../../dash/)*) {#strokedasharray}

Définit l'attribut 'stroke-dasharray' pour un élément SVG en utilisant un motif de tirets prédéfini.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, Dash value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| value | Le motif de tirets à définir. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* enum [Dash](../../dash/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
