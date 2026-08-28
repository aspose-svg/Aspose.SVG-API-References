---
title: "SVGBuilderExtensions.AddAnimateMotion"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo AddAnimateMotion di SVGBuilderExtensions. Aggiunge una configurazione dell'elemento animateMotion al builder"
type: docs
weight: 40
url: /it/net/aspose.svg.builder/svgbuilderextensions/addanimatemotion/
---
## SVGBuilderExtensions.AddAnimateMotion<TBuilder> method

Aggiunge una configurazione dell'elemento 'animateMotion' al builder.

```csharp
public static TBuilder AddAnimateMotion<TBuilder>(this TBuilder builder, 
    Action<SVGAnimateMotionElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'animateMotion'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGAnimateMotionElementBuilder](../../svganimatemotionelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationElementBuilder](../../ianimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
