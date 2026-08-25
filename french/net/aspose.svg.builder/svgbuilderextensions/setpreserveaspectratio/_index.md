---
title: "SVGBuilderExtensions.SetPreserveAspectRatio"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode SetPreserveAspectRatio de SVGBuilderExtensions. Définit l'attribut preserveAspectRatio pour un élément SVG"
type: docs
weight: 2020
url: /fr/net/aspose.svg.builder/svgbuilderextensions/setpreserveaspectratio/
---
## SVGBuilderExtensions.SetPreserveAspectRatio<TBuilder> method

Définit l'attribut 'preserveAspectRatio' pour un élément SVG.

```csharp
public static TBuilder SetPreserveAspectRatio<TBuilder>(this TBuilder builder, 
    AspectRatioAlign align, AspectRatioScaling meetOrSlice = AspectRatioScaling.Meet)
    where TBuilder : ISVGElementBuilder, IPreserveAspectRatioAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| align | Le paramètre d'alignement pour le ratio d'aspect. |
| meetOrSlice | Spécifie comment le ratio d'aspect est préservé (la valeur par défaut est 'Meet'). |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* enum [AspectRatioAlign](../../aspectratioalign/)
* enum [AspectRatioScaling](../../aspectratioscaling/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../../ipreserveaspectratioattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
