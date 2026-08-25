---
title: "SVGBuilderExtensions.AddRect"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode AddRect de SVGBuilderExtensions. Ajoute une configuration d'élément rect au constructeur."
type: docs
weight: 450
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addrect/
---
## AddRect<TBuilder>(*this TBuilder, Action&lt;SVGRectElementBuilder&gt;*) {#addrect_1}

Ajoute une configuration d'élément 'rect' au constructeur.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    Action<SVGRectElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'rect'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRect<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGRectElementBuilder&gt;*) {#addrect}

Ajoute un élément 'rect' (rectangle) avec les dimensions et styles spécifiés au constructeur SVG.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGRectElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG, facilitant l'utilisation d'une API fluide. |
| constructeur | L'instance du constructeur SVG à laquelle l'élément 'rect' sera ajouté. |
| x | La coordonnée x du point de départ du rectangle. Peut être une valeur double ou un tuple de double et LengthType. |
| y | La coordonnée y du point de départ du rectangle. Peut être une valeur double ou un tuple de double et LengthType. |
| width | La largeur du rectangle. Peut être une valeur double ou un tuple de double et LengthType. |
| hauteur | La hauteur du rectangle. Peut être une valeur double ou un tuple de double et LengthType. |
| remplissage | La couleur de remplissage ou le style de peinture pour le rectangle. Peut être un Color ou une valeur d'énumération Paint ou un ID de serveur de peinture. Paramètre optionnel. |
| trait | La couleur du trait ou le style de peinture pour le contour du rectangle. Peut être un Color ou une valeur d'énumération Paint ou un ID de serveur de peinture. Paramètre optionnel. |
| id | L'identifiant unique pour l'élément rectangle. Paramètre optionnel. |
| étendre | Une action optionnelle pour configurer davantage le constructeur d'élément rectangle. |

### Valeur de retour

L'instance du constructeur, permettant l'enchaînement des méthodes.

### Voir aussi

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
