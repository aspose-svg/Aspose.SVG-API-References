---
title: "SVGBuilderExtensions.AddLinearGradient"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode AddLinearGradient de SVGBuilderExtensions. Ajoute une configuration d'élément linearGradient au constructeur"
type: docs
weight: 360
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addlineargradient/
---
## AddLinearGradient<TBuilder>(*this TBuilder, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient_1}

Ajoute une configuration d'élément 'linearGradient' au constructeur.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    Action<SVGLinearGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'linearGradient'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLinearGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient}

Ajoute un élément 'linearGradient' au constructeur SVG, en spécifiant ses positions de départ et d'arrivée, ainsi que d'autres propriétés du dégradé.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1, OneOf<double, (double, LengthType)> y1, 
    OneOf<double, (double, LengthType)> x2, OneOf<double, (double, LengthType)> y2, 
    CoordinateUnits? gradientUnits, SpreadMethod? spreadMethod, string href = null, 
    string id = null, Action<SVGLinearGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG, facilitant l'utilisation d'une API fluide. |
| constructeur | L'instance du constructeur SVG à laquelle l'élément 'linearGradient' sera ajouté. |
| x1 | La coordonnée x de départ du dégradé. Peut être un double ou un ValueTuple avec LengthType. |
| y1 | La coordonnée y de départ du dégradé. Peut être un double ou un ValueTuple avec LengthType. |
| x2 | La coordonnée x finale du dégradé. Peut être un double ou un ValueTuple avec LengthType. |
| y2 | La coordonnée y finale du dégradé. Peut être un double ou un ValueTuple avec LengthType. |
| gradientUnits | Spécifie le système de coordonnées pour le dégradé. Paramètre optionnel. |
| spreadMethod | Définit comment le dégradé se propage au-delà de ses points de départ et d'arrivée. Paramètre optionnel. |
| href | La référence à un autre dégradé, le cas échéant. Paramètre optionnel. |
| id | L'identifiant unique pour l'élément de dégradé. Paramètre optionnel. |
| étendre | Une action optionnelle pour configurer davantage le constructeur d'élément de dégradé linéaire. |

### Valeur de retour

L'instance du constructeur, permettant l'enchaînement des méthodes.

### Voir aussi

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
