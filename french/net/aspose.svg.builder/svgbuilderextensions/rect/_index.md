---
title: "SVGBuilderExtensions.Rect"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode SVGBuilderExtensions Rect. Définit les attributs x, y, width et height pour un élément SVG afin de définir un rectangle."
type: docs
weight: 1920
url: /fr/net/aspose.svg.builder/svgbuilderextensions/rect/
---
## SVGBuilderExtensions.Rect<TBuilder> method

Définit les attributs 'x', 'y', 'width' et 'height' pour un élément SVG afin de définir un rectangle.

```csharp
public static TBuilder Rect<TBuilder>(this TBuilder builder, double x, double y, double width, 
    double height, LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRectAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| x | La coordonnée x du rectangle. |
| y | La coordonnée y du rectangle. |
| width | La largeur du rectangle. |
| hauteur | La hauteur du rectangle. |
| type | Le type de mesure de longueur pour toutes les dimensions (par défaut, pixels). |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRectAttributeSetter](../../irectattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
