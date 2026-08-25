---
title: "SVGBuilderExtensions.AddStop"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode SVGBuilderExtensions AddStop. Ajoute une configuration d'élément stop au constructeur pour définir les arrêts de dégradé."
type: docs
weight: 480
url: /fr/net/aspose.svg.builder/svgbuilderextensions/addstop/
---
## AddStop<TBuilder>(*this TBuilder, Action&lt;SVGStopElementBuilder&gt;*) {#addstop}

Ajoute une configuration d'élément 'stop' au constructeur pour définir les arrêts du dégradé.

```csharp
public static TBuilder AddStop<TBuilder>(this TBuilder builder, 
    Action<SVGStopElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG. |
| constructeur | L'instance du constructeur. |
| configurer | L'action de configuration pour l'élément 'stop'. |

### Valeur de retour

L'instance du constructeur pour l'enchaînement.

### Voir aussi

* class [SVGStopElementBuilder](../../svgstopelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddStop<TBuilder>(*this TBuilder, Color?, double?, OneOf&lt;double, (double, StopUnitType)&gt;, string, Action&lt;SVGStopElementBuilder&gt;*) {#addstop_1}

Ajoute un élément 'stop' au dégradé dans le constructeur SVG, en spécifiant la couleur et l'opacité à un certain offset.

```csharp
public static TBuilder AddStop<TBuilder>(this TBuilder builder, Color? stopColor = default, 
    double? stopOpacity = null, OneOf<double, (double, StopUnitType)> offset = null, 
    string id = null, Action<SVGStopElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| Paramètre | Description |
| --- | --- |
| TBuilder | Le type du constructeur d'éléments SVG, facilitant l'utilisation d'une API fluide. |
| constructeur | L'instance du constructeur SVG à laquelle l'élément 'stop' sera ajouté. |
| stopColor | La couleur au point d'arrêt. Paramètre optionnel. |
| stopOpacity | L'opacité au point d'arrêt. Paramètre optionnel. |
| offset | Le décalage du point d'arrêt dans le dégradé. Peut être un double ou un ValueTuple avec StopUnitType. Paramètre optionnel. |
| id | L'identifiant unique de l'élément stop. Paramètre optionnel. |
| étendre | Une action optionnelle pour configurer davantage le constructeur d'élément stop. |

### Valeur de retour

L'instance du constructeur, permettant l'enchaînement des méthodes.

### Voir aussi

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [StopUnitType](../../stopunittype/)
* class [SVGStopElementBuilder](../../svgstopelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
