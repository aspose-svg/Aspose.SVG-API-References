---
title: "SVGBuilderExtensions.AddFilter"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode AddFilter de SVGBuilderExtensions. Ajoute une configuration d'élément filtre au constructeur."
type: docs
weight: 300
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addfilter/
---
## AddFilter<TBuilder>(*this TBuilder, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter}

Ajoute une configuration d'élément 'filter' au constructeur.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    Action<SVGFilterElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'filter'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFilter<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter_1}

Ajoute un élément 'filter' au constructeur SVG, définissant un effet de filtre pouvant être appliqué aux éléments SVG.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    CoordinateUnits? filterUnits = default, CoordinateUnits? primitiveUnits = default, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFilterElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG, facilitant l'utilisation d'une API fluide. |
| constructeur | L'instance du constructeur SVG à laquelle l'élément 'filter' sera ajouté. |
| filterUnits | Spécifie le système de coordonnées pour les attributs x, y, width et height du filtre. Paramètre optionnel. |
| primitiveUnits | Spécifie le système de coordonnées pour les attributs des éléments enfants du filtre. Paramètre optionnel. |
| x | La coordonnée x de la région du filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| y | La coordonnée y de la région du filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| width | La largeur de la région du filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| hauteur | La hauteur de la région du filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| remplissage | La couleur de remplissage ou la peinture pour l'élément de filtre. Paramètre optionnel. |
| trait | La couleur du trait ou la peinture pour l'élément de filtre. Paramètre optionnel. |
| id | L'identifiant unique pour l'élément de filtre. Paramètre optionnel. |
| étendre | Une action optionnelle pour configurer davantage le SVGFilterElementBuilder. |

### Valeur de retour

L'instance du constructeur, permettant l'enchaînement des méthodes.

### Voir aussi

* enum [CoordinateUnits](../../coordinateunits/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
