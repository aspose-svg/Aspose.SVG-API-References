---
title: "SVGBuilderExtensions.Color"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode Color de SVGBuilderExtensions. Définit l'attribut color pour un élément SVG en utilisant une configuration personnalisée"
type: docs
weight: 670
url: /fr/net/aspose.svg.builder/svgbuilderextensions/color/
---
## Color<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#color}

Définit l'attribut 'color' pour un élément SVG en utilisant une configuration personnalisée.

```csharp
public static TBuilder Color<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | Un délégué pour configurer la couleur. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [ColorBuilder](../../colorbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Color<TBuilder>(*this TBuilder, Color*) {#color_1}

Définit l'attribut 'color' pour un élément SVG en utilisant une valeur de couleur.

```csharp
public static TBuilder Color<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| colorValue | La valeur de couleur à définir. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
