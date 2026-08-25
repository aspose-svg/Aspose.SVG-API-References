---
title: "SVGBuilderExtensions.AddFeDropShadow"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode AddFeDropShadow de SVGBuilderExtensions. Ajoute une configuration d'élément feDropShadow au constructeur. Cet élément crée un effet d'ombre portée"
type: docs
weight: 200
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addfedropshadow/
---
## AddFeDropShadow<TBuilder>(*this TBuilder, Action&lt;SVGFEDropShadowElementBuilder&gt;*) {#addfedropshadow}

Ajoute une configuration d'élément 'feDropShadow' au constructeur. Cet élément crée un effet d'ombre portée.

```csharp
public static TBuilder AddFeDropShadow<TBuilder>(this TBuilder builder, 
    Action<SVGFEDropShadowElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'feDropShadow'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGFEDropShadowElementBuilder](../../svgfedropshadowelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDropShadow<TBuilder>(*this TBuilder, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDropShadowElementBuilder&gt;*) {#addfedropshadow_1}

Ajoute un élément 'feDropShadow' au constructeur SVG, créant un effet d'ombre portée pour le graphique d'entrée.

```csharp
public static TBuilder AddFeDropShadow<TBuilder>(this TBuilder builder, double? dx = null, 
    double? dy = null, OneOf<double, (double, double)> stdDeviation = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDropShadowElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG, facilitant l'utilisation d'une API fluide. |
| constructeur | L'instance du constructeur SVG à laquelle l'élément 'feDropShadow' sera ajouté. |
| dx | Le décalage horizontal pour l'ombre portée. Paramètre optionnel. |
| dy | Le décalage vertical pour l'ombre portée. Paramètre optionnel. |
| stdDeviation | L'écart type pour l'opération de flou dans l'ombre portée. Peut être un double ou un ValueTuple de deux doubles. Paramètre optionnel. |
| in | Le graphique d'entrée auquel l'ombre portée sera appliquée. Peut être une chaîne ou un FilterInput. Paramètre optionnel. |
| result | L'identifiant du résultat pour cette primitive de filtre. Paramètre optionnel. |
| x | La coordonnée x de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| y | La coordonnée y de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| width | La largeur de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| hauteur | La hauteur de la sous-région primitive du filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| remplissage | La couleur de remplissage, la peinture ou l'ID du serveur de peinture pour l'élément. Paramètre optionnel. |
| trait | La couleur du trait, la peinture ou l'ID du serveur de peinture pour l'élément. Paramètre optionnel. |
| id | L'identifiant unique pour l'élément primitive du filtre. Paramètre optionnel. |
| étendre | Une action optionnelle pour configurer davantage le SVGFEDropShadowElementBuilder. |

### Valeur de retour

L'instance du constructeur, permettant l'enchaînement des méthodes.

### Voir aussi

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDropShadowElementBuilder](../../svgfedropshadowelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
