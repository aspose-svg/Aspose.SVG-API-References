---
title: "SVGBuilderExtensions.AddRadialGradient"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode SVGBuilderExtensions AddRadialGradient. Ajoute une configuration d'élément radialGradient au builder"
type: docs
weight: 440
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addradialgradient/
---
## AddRadialGradient<TBuilder>(*this TBuilder, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient_1}

Ajoute une configuration d'élément 'radialGradient' au constructeur.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    Action<SVGRadialGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'radialGradient'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRadialGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient}

Ajoute un élément 'radialGradient' au constructeur SVG, en spécifiant son centre, son rayon et ses points focaux, ainsi que d'autres propriétés du dégradé.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<double, (double, LengthType)> fx = null, 
    OneOf<double, (double, LengthType)> fy = null, CoordinateUnits? gradientUnits = default, 
    SpreadMethod? spreadMethod = default, string href = null, string id = null, 
    Action<SVGRadialGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG, facilitant l'utilisation d'une API fluide. |
| constructeur | L'instance du constructeur SVG à laquelle l'élément 'radialGradient' sera ajouté. |
| cx | La coordonnée x du centre du dégradé. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| cy | La coordonnée y du centre du dégradé. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| r | Le rayon du dégradé. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| fx | La coordonnée x du point focal du dégradé. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| fy | La coordonnée y du point focal du dégradé. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| gradientUnits | Spécifie le système de coordonnées pour le dégradé. Paramètre optionnel. |
| spreadMethod | Définit comment le dégradé se propage au-delà de ses points de départ et d'arrivée. Paramètre optionnel. |
| href | La référence à un autre dégradé, le cas échéant. Paramètre optionnel. |
| id | L'identifiant unique pour l'élément de dégradé. Paramètre optionnel. |
| étendre | Une action optionnelle pour configurer davantage le constructeur d'élément de dégradé radial. |

### Valeur de retour

L'instance du constructeur, permettant l'enchaînement des méthodes.

### Voir aussi

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
