---
title: "SVGBuilderExtensions.AddText"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode AddText de SVGBuilderExtensions. Ajoute une configuration d'élément texte au constructeur"
type: docs
weight: 530
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addtext/
---
## AddText<TBuilder>(*this TBuilder, Action&lt;SVGTextElementBuilder&gt;*) {#addtext}

Ajoute une configuration d'élément 'text' au constructeur.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, 
    Action<SVGTextElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'text'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddText<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, FontStyle?, string, FontWeight?, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGTextElementBuilder&gt;*) {#addtext_1}

Ajoute un élément 'text' avec le contenu et les attributs spécifiés au constructeur SVG.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, string content, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> fontSize = null, FontStyle? fontStyle = default, 
    string fontFamily = null, FontWeight? fontWeight = default, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGTextElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG, permettant l'enchaînement. |
| constructeur | L'instance du constructeur à laquelle l'élément 'text' sera ajouté. |
| contenu | Le contenu texte à afficher dans l'élément 'text'. |
| x | La coordonnée x de l'élément texte. Peut être une valeur double ou un tuple de double et LengthType. |
| y | La coordonnée y de l'élément texte. Peut être une valeur double ou un tuple de double et LengthType. |
| taillePolice | La taille de police du texte. Peut être une valeur double ou un tuple de double et LengthType. |
| stylePolice | Le style de police du texte (par ex., normal, italique, oblique). |
| famillePolice | La famille de police du texte (par ex., Arial, Verdana). |
| épaisseurPolice | L'épaisseur (épaisseur) de la police (par ex., normal, gras). |
| remplissage | La couleur de remplissage ou le style de peinture du texte. Peut être un Color ou une valeur d'énumération Paint ou un ID de serveur de peinture. |
| trait | La couleur de contour ou le style de peinture du texte. Peut être un Color ou une valeur d'énumération Paint ou un ID de serveur de peinture. |
| id | L'identifiant unique de l'élément texte. |
| étendre | Une action facultative pour configurer davantage le constructeur d'élément texte. |

### Valeur de retour

L'instance du constructeur pour chaîner d'autres ajouts ou configurations.

### Voir aussi

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [FontStyle](../../fontstyle/)
* enum [FontWeight](../../fontweight/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
