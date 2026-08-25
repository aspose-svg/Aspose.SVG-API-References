---
title: "SVGBuilderExtensions.RequiredExtensions"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode SVGBuilderExtensions RequiredExtensions. Définit l'attribut requiredExtensions sur l'élément SVG. Cet attribut spécifie quelles extensions sont requises pour que le fragment de document SVG soit traité"
type: docs
weight: 1970
url: /fr/net/aspose.svg.builder/svgbuilderextensions/requiredextensions/
---
## SVGBuilderExtensions.RequiredExtensions<TBuilder> method

Définit l'attribut 'requiredExtensions' sur l'élément SVG. Cet attribut indique quelles extensions sont requises pour que le fragment de document SVG soit traité.

```csharp
public static TBuilder RequiredExtensions<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IConditionalProcessingAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'élément SVG sur lequel l'attribut est défini. |
| value | Une valeur chaîne représentant les extensions requises. |

### Valeur de retour

Le constructeur d'élément SVG original pour l'enchaînement de méthodes.

### Voir aussi

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../../iconditionalprocessingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
