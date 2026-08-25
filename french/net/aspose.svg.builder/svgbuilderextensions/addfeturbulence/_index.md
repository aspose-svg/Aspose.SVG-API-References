---
title: "SVGBuilderExtensions.AddFeTurbulence"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode AddFeTurbulence de SVGBuilderExtensions. Ajoute une configuration d'élément feTurbulence au constructeur. Cet élément crée une image à l'aide du bruit de Perlin, utile pour créer des textures comme des nuages ou du marbre."
type: docs
weight: 290
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addfeturbulence/
---
## AddFeTurbulence<TBuilder>(*this TBuilder, Action&lt;SVGFETurbulenceElementBuilder&gt;*) {#addfeturbulence_1}

Ajoute une configuration d'élément 'feTurbulence' au constructeur. Cet élément crée une image en utilisant le bruit de Perlin, utile pour créer des textures comme des nuages ou du marbre.

```csharp
public static TBuilder AddFeTurbulence<TBuilder>(this TBuilder builder, 
    Action<SVGFETurbulenceElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'feTurbulence'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGFETurbulenceElementBuilder](../../svgfeturbulenceelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeTurbulence<TBuilder>(*this TBuilder, OneOf&lt;double, (double, double)&gt;, int?, double?, StitchTiles?, TurbulenceType?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFETurbulenceElementBuilder&gt;*) {#addfeturbulence}

Ajoute un élément 'feTurbulence' au constructeur SVG, créant un effet de turbulence, tel que des nuages ou du marbre, en utilisant le bruit de Perlin.

```csharp
public static TBuilder AddFeTurbulence<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, double)> baseFrequency = null, int? numOctaves = null, 
    double? seed = null, StitchTiles? stitchTiles = default, TurbulenceType? type = default, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFETurbulenceElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG, facilitant l'utilisation d'une API fluide. |
| constructeur | L'instance du constructeur SVG à laquelle l'élément 'feTurbulence' sera ajouté. |
| baseFrequency | La fréquence de base de la turbulence. Peut être un double ou un ValueTuple de deux doubles. Paramètre optionnel. |
| numOctaves | Le nombre d'octaves pour la turbulence. Paramètre optionnel. |
| seed | Le nombre de graine pour le générateur de nombres aléatoires. Paramètre optionnel. |
| stitchTiles | Indique si les tuiles sont assemblées. Paramètre optionnel. |
| type | Le type de turbulence (bruit fractal ou turbulence). Paramètre optionnel. |
| in | L'image d'entrée à laquelle l'effet de turbulence sera appliqué. Peut être une chaîne ou un FilterInput. Paramètre optionnel. |
| result | L'identifiant du résultat pour cette primitive de filtre. Paramètre optionnel. |
| x | La coordonnée x de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| y | La coordonnée y de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| width | La largeur de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| hauteur | La hauteur de la sous-région primitive du filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| remplissage | La couleur de remplissage, la peinture ou l'ID du serveur de peinture pour l'élément. Paramètre optionnel. |
| trait | La couleur du trait, la peinture ou l'ID du serveur de peinture pour l'élément. Paramètre optionnel. |
| id | L'identifiant unique pour l'élément primitive du filtre. Paramètre optionnel. |
| étendre | Une action optionnelle pour configurer davantage le SVGFETurbulenceElementBuilder. |

### Valeur de retour

L'instance du constructeur, permettant l'enchaînement des méthodes.

### Voir aussi

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [StitchTiles](../../stitchtiles/)
* enum [TurbulenceType](../../turbulencetype/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFETurbulenceElementBuilder](../../svgfeturbulenceelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
