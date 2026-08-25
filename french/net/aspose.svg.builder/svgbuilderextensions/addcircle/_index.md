---
title: "SVGBuilderExtensions.AddCircle"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode AddCircle de SVGBuilderExtensions. Ajoute une configuration d'élément cercle au constructeur"
type: docs
weight: 70
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addcircle/
---
## AddCircle<TBuilder>(*this TBuilder, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle_1}

Ajoute une configuration d'élément 'circle' au constructeur.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    Action<SVGCircleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'circle'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddCircle<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle}

Ajoute un élément 'circle' avec le centre, le rayon et les styles spécifiés au constructeur SVG.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGCircleElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG, facilitant l'utilisation d'une API fluide. |
| constructeur | L'instance du constructeur SVG à laquelle l'élément 'circle' sera ajouté. |
| cx | La coordonnée x du centre du cercle. Peut être une valeur double ou un tuple de double et LengthType. |
| cy | La coordonnée y du centre du cercle. Peut être une valeur double ou un tuple de double et LengthType. |
| r | Le rayon du cercle. Peut être une valeur double ou un tuple de double et LengthType. |
| remplissage | La couleur de remplissage ou le style de peinture pour le cercle. Peut être un Color, une valeur d'énumération Paint ou un ID de serveur de peinture. Paramètre optionnel. |
| trait | La couleur du trait ou le style de peinture pour le contour du cercle. Peut être un Color, une valeur d'énumération Paint ou un ID de serveur de peinture. Paramètre optionnel. |
| id | L'identifiant unique pour l'élément cercle. Paramètre optionnel. |
| étendre | Une action optionnelle pour configurer davantage le constructeur d'élément cercle. |

### Valeur de retour

L'instance du constructeur, permettant l'enchaînement des méthodes.

### Voir aussi

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
