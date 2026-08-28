---
title: "SVGBuilderExtensions.AddAnimateTransform"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions AddAnimateTransform. Aggiunge una configurazione dell'elemento animateTransform al builder"
type: docs
weight: 50
url: /it/net/aspose.svg.builder/svgbuilderextensions/addanimatetransform/
---
## SVGBuilderExtensions.AddAnimateTransform<TBuilder> method

Aggiunge una configurazione dell'elemento 'animateTransform' al builder.

```csharp
public static TBuilder AddAnimateTransform<TBuilder>(this TBuilder builder, 
    Action<SVGAnimateTransformElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'animateTransform'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGAnimateTransformElementBuilder](../../svganimatetransformelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationElementBuilder](../../ianimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
