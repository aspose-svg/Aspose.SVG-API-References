---
title: "SVGBuilderExtensions.AddEllipse"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode AddEllipse de SVGBuilderExtensions. Ajoute une configuration d'élément ellipse au constructeur"
type: docs
weight: 120
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addellipse/
---
## AddEllipse<TBuilder>(*this TBuilder, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse_1}

Ajoute une configuration d'élément 'ellipse' au constructeur.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    Action<SVGEllipseElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément « ellipse ». |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddEllipse<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse}

Ajoute un élément 'ellipse' au constructeur SVG, en spécifiant son centre, ses rayons et ses styles.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> rx = null, OneOf<double, (double, LengthType)> ry = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGEllipseElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG, facilitant l'utilisation d'une API fluide. |
| constructeur | L'instance du constructeur SVG à laquelle l'élément « ellipse » sera ajouté. |
| cx | La coordonnée x du centre de l'ellipse. Peut être une valeur double ou un tuple de double et LengthType. |
| cy | La coordonnée y du centre de l'ellipse. Peut être une valeur double ou un tuple de double et LengthType. |
| rx | Le rayon x de l'ellipse. Peut être une valeur double ou un tuple de double et LengthType. |
| ry | Le rayon y de l'ellipse. Peut être une valeur double ou un tuple de double et LengthType. |
| remplissage | La couleur de remplissage ou le style de peinture pour l'ellipse. Peut être un Color ou une valeur d'énumération Paint ou un ID de serveur de peinture. Paramètre optionnel. |
| trait | La couleur du trait ou le style de peinture pour l'ellipse. Peut être un Color ou une valeur d'énumération Paint ou un ID de serveur de peinture. Paramètre optionnel. |
| id | L'identifiant unique pour l'élément ellipse. Paramètre optionnel. |
| étendre | Une action optionnelle pour configurer davantage le constructeur d'élément ellipse. |

### Valeur de retour

L'instance du constructeur, permettant l'enchaînement des méthodes.

### Voir aussi

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
