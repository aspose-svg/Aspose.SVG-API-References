---
title: "SVGBuilderExtensions.AddFeBlend"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode SVGBuilderExtensions AddFeBlend. Ajoute une configuration d'élément feBlend au constructeur. Cet élément définit un effet de fusion entre deux graphiques"
type: docs
weight: 130
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addfeblend/
---
## AddFeBlend<TBuilder>(*this TBuilder, Action&lt;SVGFEBlendElementBuilder&gt;*) {#addfeblend}

Ajoute une configuration d'élément 'feBlend' au constructeur. Cet élément définit un effet de fusion entre deux graphiques.

```csharp
public static TBuilder AddFeBlend<TBuilder>(this TBuilder builder, 
    Action<SVGFEBlendElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'feBlend'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGFEBlendElementBuilder](../../svgfeblendelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeBlend<TBuilder>(*this TBuilder, BlendMode?, OneOf&lt;string, FilterInput&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEBlendElementBuilder&gt;*) {#addfeblend_1}

Ajoute un élément 'feBlend' au constructeur SVG, en spécifiant le mode de fusion et diverses autres propriétés pour l'effet de filtre.

```csharp
public static TBuilder AddFeBlend<TBuilder>(this TBuilder builder, BlendMode? mode = default, 
    OneOf<string, FilterInput> @in = null, OneOf<string, FilterInput> in2 = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEBlendElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG, facilitant l'utilisation d'une API fluide. |
| constructeur | L'instance du constructeur SVG à laquelle l'élément 'feBlend' sera ajouté. |
| mode | Le mode de fusion à utiliser. Paramètre optionnel. |
| in | La première entrée pour l'effet de fusion. Peut être une chaîne ou un FilterInput. Paramètre optionnel. |
| in2 | La deuxième entrée pour l'effet de fusion. Peut être une chaîne ou un FilterInput. Paramètre optionnel. |
| result | L'identifiant du résultat pour cette primitive de filtre. Paramètre optionnel. |
| x | La coordonnée x de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| y | La coordonnée y de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| width | La largeur de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| hauteur | La hauteur de la sous-région primitive du filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| remplissage | La couleur de remplissage, la peinture ou l'ID du serveur de peinture pour l'élément. Paramètre optionnel. |
| trait | La couleur du trait, la peinture ou l'ID du serveur de peinture pour l'élément. Paramètre optionnel. |
| id | L'identifiant unique pour l'élément primitive du filtre. Paramètre optionnel. |
| étendre | Une action optionnelle pour configurer davantage le SVGFEBlendElementBuilder. |

### Valeur de retour

L'instance du constructeur, permettant l'enchaînement des méthodes.

### Voir aussi

* enum [BlendMode](../../blendmode/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEBlendElementBuilder](../../svgfeblendelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
