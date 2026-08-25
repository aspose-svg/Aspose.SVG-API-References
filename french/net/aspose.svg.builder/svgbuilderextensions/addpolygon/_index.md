---
title: "SVGBuilderExtensions.AddPolygon"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode SVGBuilderExtensions AddPolygon. Ajoute une configuration d'élément polygon au constructeur"
type: docs
weight: 420
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addpolygon/
---
## AddPolygon<TBuilder>(*this TBuilder, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon_1}

Ajoute une configuration d'élément 'polygon' au constructeur.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, 
    Action<SVGPolygonElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'polygon'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolygon<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon}

Ajoute un élément 'polygon' au constructeur SVG, en spécifiant ses sommets et ses styles.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolygonElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG, facilitant l'utilisation d'une API fluide. |
| constructeur | L'instance du constructeur SVG à laquelle l'élément 'polygon' sera ajouté. |
| points | Un tableau de doubles représentant les points du polygone (coordonnées x et y alternées). |
| remplissage | La couleur de remplissage ou le style de peinture du polygone. Peut être une valeur d'énumération Color ou Paint ou un ID de serveur de peinture. Paramètre optionnel. |
| trait | La couleur du trait ou le style de peinture du polygone. Peut être une valeur d'énumération Color ou Paint ou un ID de serveur de peinture. Paramètre optionnel. |
| id | L'identifiant unique de l'élément polygone. Paramètre optionnel. |
| étendre | Une action optionnelle pour configurer davantage le constructeur d'élément polygone. |

### Valeur de retour

L'instance du constructeur, permettant l'enchaînement des méthodes.

### Voir aussi

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
