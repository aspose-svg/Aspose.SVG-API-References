---
title: "SVGBuilderExtensions.Style"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode Style de SVGBuilderExtensions. Définit l'attribut style en utilisant un constructeur de règles pour définir les styles CSS"
type: docs
weight: 2160
url: /fr/net/aspose.svg.builder/svgbuilderextensions/style/
---
## Style<TBuilder>(*this TBuilder, Action&lt;RuleBuilder&gt;*) {#style}

Définit l'attribut 'style' en utilisant un constructeur de règles pour définir les styles CSS.

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, Action<RuleBuilder> configureRule)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| configureRule | L'action pour configurer la règle CSS. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [RuleBuilder](../../rulebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Style<TBuilder>(*this TBuilder, string*) {#style_1}

Définit l'attribut 'style', définissant les styles CSS en ligne pour l'élément SVG.

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, string rules)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | Le constructeur d'éléments SVG. |
| rules | Les règles CSS sous forme de chaîne. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
