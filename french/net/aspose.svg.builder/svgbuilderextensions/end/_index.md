---
title: "SVGBuilderExtensions.End"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode End de SVGBuilderExtensions. Définit l'attribut end indiquant quand l'animation doit se terminer"
type: docs
weight: 790
url: /fr/net/aspose.svg.builder/svgbuilderextensions/end/
---
## SVGBuilderExtensions.End<TBuilder> method

Définit l'attribut 'end', en définissant le moment où l'animation doit se terminer.

```csharp
public static TBuilder End<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| configurer | Un délégué pour configurer la valeur de synchronisation. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [TimingValueBuilder](../../timingvaluebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
