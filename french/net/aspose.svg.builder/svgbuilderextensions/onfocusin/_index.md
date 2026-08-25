---
title: "SVGBuilderExtensions.OnFocusIn"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode SVGBuilderExtensions OnFocusIn. Définit l'attribut d'événement onfocusin pour gérer les événements de focus-in sur l'élément."
type: docs
weight: 1450
url: /fr/net/aspose.svg.builder/svgbuilderextensions/onfocusin/
---
## SVGBuilderExtensions.OnFocusIn<TBuilder> method

Définit l'attribut d'événement 'onfocusin' pour gérer les événements de focus entrant sur l'élément.

```csharp
public static TBuilder OnFocusIn<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| value | La fonction ou le script JavaScript à exécuter lorsque l'élément reçoit le focus, généralement avant l'événement 'onfocus'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

## Remarques

L'événement 'onfocusin' est déclenché lorsqu'un élément est sur le point de recevoir le focus. Cet événement diffère de 'onfocus' car il prend en charge la propagation et peut également être utilisé pour détecter les changements de focus sur les éléments enfants.

### Voir aussi

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
