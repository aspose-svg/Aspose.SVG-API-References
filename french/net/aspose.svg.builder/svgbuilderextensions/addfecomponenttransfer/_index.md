---
title: "SVGBuilderExtensions.AddFeComponentTransfer"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode AddFeComponentTransfer de SVGBuilderExtensions. Ajoute une configuration d'élément feComponentTransfer au constructeur. Cet élément effectue un remappage composant par composant des données pour les canaux de couleur"
type: docs
weight: 150
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addfecomponenttransfer/
---
## AddFeComponentTransfer<TBuilder>(*this TBuilder, Action&lt;SVGFEComponentTransferElementBuilder&gt;*) {#addfecomponenttransfer}

Ajoute une configuration d'élément 'feComponentTransfer' au constructeur. Cet élément effectue un remappage composant par composant des données pour les canaux de couleur.

```csharp
public static TBuilder AddFeComponentTransfer<TBuilder>(this TBuilder builder, 
    Action<SVGFEComponentTransferElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'feComponentTransfer'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGFEComponentTransferElementBuilder](../../svgfecomponenttransferelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeComponentTransfer<TBuilder>(*this TBuilder, Action&lt;SVGFEFuncAElementBuilder&gt;, Action&lt;SVGFEFuncRElementBuilder&gt;, Action&lt;SVGFEFuncGElementBuilder&gt;, Action&lt;SVGFEFuncBElementBuilder&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEComponentTransferElementBuilder&gt;*) {#addfecomponenttransfer_1}

Ajoute un élément 'feComponentTransfer' au constructeur SVG, permettant un remappage composant par composant des données pour les canaux de couleur.

```csharp
public static TBuilder AddFeComponentTransfer<TBuilder>(this TBuilder builder, 
    Action<SVGFEFuncAElementBuilder> a = null, Action<SVGFEFuncRElementBuilder> r = null, 
    Action<SVGFEFuncGElementBuilder> g = null, Action<SVGFEFuncBElementBuilder> b = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEComponentTransferElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG, facilitant l'utilisation d'une API fluide. |
| constructeur | L'instance du constructeur SVG à laquelle l'élément 'feComponentTransfer' sera ajouté. |
| a | Une action pour configurer le composant 'feFuncA' pour le canal alpha. Paramètre optionnel. |
| r | Une action pour configurer le composant 'feFuncR' pour le canal rouge. Paramètre optionnel. |
| g | Une action pour configurer le composant 'feFuncG' pour le canal vert. Paramètre optionnel. |
| b | Une action pour configurer le composant 'feFuncB' pour le canal bleu. Paramètre optionnel. |
| in | L'entrée pour l'effet de transfert de composant. Peut être une chaîne ou un FilterInput. Paramètre optionnel. |
| result | L'identifiant du résultat pour cette primitive de filtre. Paramètre optionnel. |
| x | La coordonnée x de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| y | La coordonnée y de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| width | La largeur de la sous-région de cette primitive de filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| hauteur | La hauteur de la sous-région primitive du filtre. Peut être un double ou un ValueTuple avec LengthType. Paramètre optionnel. |
| remplissage | La couleur de remplissage, la peinture ou l'ID du serveur de peinture pour l'élément. Paramètre optionnel. |
| trait | La couleur du trait, la peinture ou l'ID du serveur de peinture pour l'élément. Paramètre optionnel. |
| id | L'identifiant unique pour l'élément primitive du filtre. Paramètre optionnel. |
| étendre | Une action optionnelle pour configurer davantage le SVGFEComponentTransferElementBuilder. |

### Valeur de retour

L'instance du constructeur, permettant l'enchaînement des méthodes.

### Voir aussi

* class [SVGFEFuncAElementBuilder](../../svgfefuncaelementbuilder/)
* class [SVGFEFuncRElementBuilder](../../svgfefuncrelementbuilder/)
* class [SVGFEFuncGElementBuilder](../../svgfefuncgelementbuilder/)
* class [SVGFEFuncBElementBuilder](../../svgfefuncbelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEComponentTransferElementBuilder](../../svgfecomponenttransferelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
