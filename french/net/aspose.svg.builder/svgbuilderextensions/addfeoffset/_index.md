---
title: "SVGBuilderExtensions.AddFeOffset"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode SVGBuilderExtensions AddFeOffset. Ajoute une configuration d'élément feOffset au constructeur. Cet élément décale l'image d'entrée selon un vecteur spécifié"
type: docs
weight: 260
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addfeoffset/
---
## AddFeOffset<TBuilder>(*this TBuilder, Action&lt;SVGFEOffsetElementBuilder&gt;*) {#addfeoffset}

Ajoute une configuration d'élément 'feOffset' au constructeur. Cet élément décale l'image d'entrée selon un vecteur spécifié.

```csharp
public static TBuilder AddFeOffset<TBuilder>(this TBuilder builder, 
    Action<SVGFEOffsetElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'feOffset'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGFEOffsetElementBuilder](../../svgfeoffsetelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeOffset<TBuilder>(*this TBuilder, double?, double?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEOffsetElementBuilder&gt;*) {#addfeoffset_1}

Ajoute un élément 'feOffset' au constructeur SVG, créant un effet de décalage en déplaçant l'image d'entrée selon un vecteur spécifié.

```csharp
public static TBuilder AddFeOffset<TBuilder>(this TBuilder builder, double? dx = null, 
    double? dy = null, OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEOffsetElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG, facilitant l'utilisation d'une API fluide. |
| constructeur | L'instance du constructeur SVG à laquelle l'élément 'feOffset' sera ajouté. |
| dx | La distance de décalage horizontale. Paramètre optionnel. |
| dy | La distance de décalage verticale. Paramètre optionnel. |
| in | L'image d'entrée à laquelle le décalage sera appliqué. Peut être une chaîne ou un FilterInput. Paramètre optionnel. |
| result | L'identifiant du résultat pour cette primitive de filtre. Paramètre optionnel. |
| x | La coordonnée x de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| y | La coordonnée y de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| width | La largeur de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| hauteur | La hauteur de la sous-région primitive du filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| remplissage | La couleur de remplissage, la peinture ou l'ID du serveur de peinture pour l'élément. Paramètre optionnel. |
| trait | La couleur du trait, la peinture ou l'ID du serveur de peinture pour l'élément. Paramètre optionnel. |
| id | L'identifiant unique pour l'élément primitive du filtre. Paramètre optionnel. |
| étendre | Une action optionnelle pour configurer davantage le SVGFEOffsetElementBuilder. |

### Valeur de retour

L'instance du constructeur, permettant l'enchaînement des méthodes.

### Voir aussi

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEOffsetElementBuilder](../../svgfeoffsetelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
