---
title: "SVGBuilderExtensions.AddFeConvolveMatrix"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode AddFeConvolveMatrix de SVGBuilderExtensions. Ajoute une configuration d'élément feConvolveMatrix au constructeur. Cet élément applique un effet de filtre de convolution matricielle"
type: docs
weight: 170
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addfeconvolvematrix/
---
## AddFeConvolveMatrix<TBuilder>(*this TBuilder, Action&lt;SVGFEConvolveMatrixElementBuilder&gt;*) {#addfeconvolvematrix_1}

Ajoute une configuration d'élément 'feConvolveMatrix' au constructeur. Cet élément applique un effet de filtre de convolution matricielle.

```csharp
public static TBuilder AddFeConvolveMatrix<TBuilder>(this TBuilder builder, 
    Action<SVGFEConvolveMatrixElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'feConvolveMatrix'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGFEConvolveMatrixElementBuilder](../../svgfeconvolvematrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeConvolveMatrix<TBuilder>(*this TBuilder, double[], double?, double?, int?, int?, EdgeMode?, bool?, OneOf&lt;int, (int, int)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEConvolveMatrixElementBuilder&gt;*) {#addfeconvolvematrix}

Ajoute un élément 'feConvolveMatrix' au constructeur SVG, appliquant un effet de filtre de convolution matricielle.

```csharp
public static TBuilder AddFeConvolveMatrix<TBuilder>(this TBuilder builder, 
    double[] kernelMatrix = null, double? divisor = null, double? bias = null, int? targetX = null, 
    int? targetY = null, EdgeMode? edgeMode = default, bool? preserveAlpha = null, 
    OneOf<int, (int, int)> order = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEConvolveMatrixElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG, facilitant l'utilisation d'une API fluide. |
| constructeur | L'instance du constructeur SVG à laquelle l'élément 'feConvolveMatrix' sera ajouté. |
| kernelMatrix | La matrice de valeurs pour la convolution. Paramètre optionnel. |
| divisor | Le diviseur pour la convolution. Paramètre optionnel. |
| bias | Le biais à ajouter au résultat de la convolution. Paramètre optionnel. |
| targetX | La coordonnée x du pixel cible dans la matrice du noyau. Paramètre optionnel. |
| targetY | La coordonnée y du pixel cible dans la matrice du noyau. Paramètre optionnel. |
| edgeMode | Définit comment gérer les pixels de bord dans la convolution. Paramètre optionnel. |
| preserveAlpha | Indique s'il faut préserver le canal alpha. Paramètre optionnel. |
| order | L'ordre de la matrice du noyau. Peut être un int ou un ValueTuple de deux ints. Paramètre optionnel. |
| in | L'entrée pour l'effet de convolution. Peut être une chaîne ou un FilterInput. Paramètre optionnel. |
| result | L'identifiant du résultat pour cette primitive de filtre. Paramètre optionnel. |
| x | La coordonnée x de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| y | La coordonnée y de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| width | La largeur de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| hauteur | La hauteur de la sous-région primitive du filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| remplissage | La couleur de remplissage, la peinture ou l'ID du serveur de peinture pour l'élément. Paramètre optionnel. |
| trait | La couleur du trait, la peinture ou l'ID du serveur de peinture pour l'élément. Paramètre optionnel. |
| id | L'identifiant unique pour l'élément primitive du filtre. Paramètre optionnel. |
| étendre | Une action optionnelle pour configurer davantage le SVGFEConvolveMatrixElementBuilder. |

### Valeur de retour

L'instance du constructeur, permettant l'enchaînement des méthodes.

### Voir aussi

* enum [EdgeMode](../../edgemode/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEConvolveMatrixElementBuilder](../../svgfeconvolvematrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
