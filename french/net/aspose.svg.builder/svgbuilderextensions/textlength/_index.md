---
title: "SVGBuilderExtensions.TextLength"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode TextLength de SVGBuilderExtensions. Définit la longueur exacte du contenu texte"
type: docs
weight: 2220
url: /fr/net/aspose.svg.builder/svgbuilderextensions/textlength/
---
## SVGBuilderExtensions.TextLength<TBuilder> method

Définit la longueur exacte du contenu texte.

```csharp
public static TBuilder TextLength<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| value | La longueur du texte. |
| type | Le type d'unité de longueur pour la valeur. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

## Remarques

Cette méthode définit l'attribut 'textLength', spécifiant la longueur souhaitée du contenu texte, pouvant éventuellement remplacer la longueur naturelle du texte.

### Voir aussi

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
