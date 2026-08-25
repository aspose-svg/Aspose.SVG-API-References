---
title: "SVGBuilderExtensions.OnFocusOut"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode OnFocusOut de SVGBuilderExtensions. Définit l'attribut d'événement onfocusout pour gérer les événements de perte de focus sur l'élément"
type: docs
weight: 1460
url: /fr/net/aspose.svg.builder/svgbuilderextensions/onfocusout/
---
## SVGBuilderExtensions.OnFocusOut<TBuilder> method

Définit l'attribut d'événement 'onfocusout' pour gérer les événements de focus sortant sur l'élément.

```csharp
public static TBuilder OnFocusOut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| value | La fonction ou le script JavaScript à exécuter lorsque l'élément perd le focus, généralement avant l'événement 'onblur'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

## Remarques

L'événement 'onfocusout' est déclenché lorsqu'un élément est sur le point de perdre le focus. Similaire à 'onfocusin', cet événement supporte la propagation et peut également être utilisé pour détecter les changements de focus sur les éléments enfants.

### Voir aussi

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
