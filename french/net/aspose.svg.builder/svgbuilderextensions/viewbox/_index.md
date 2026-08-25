---
title: "SVGBuilderExtensions.ViewBox"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode ViewBox de SVGBuilderExtensions. Définit l'attribut viewBox pour un élément SVG"
type: docs
weight: 2300
url: /fr/net/aspose.svg.builder/svgbuilderextensions/viewbox/
---
## SVGBuilderExtensions.ViewBox<TBuilder> method

Définit l'attribut 'viewBox' pour un élément SVG.

```csharp
public static TBuilder ViewBox<TBuilder>(this TBuilder builder, double minX, double minY, 
    double width, double height)
    where TBuilder : ISVGElementBuilder, IViewBoxAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| minX | La coordonnée X minimale du viewBox. |
| minY | La coordonnée Y minimale du viewBox. |
| width | La largeur du viewBox. |
| hauteur | La hauteur du viewBox. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IViewBoxAttributeSetter](../../iviewboxattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
