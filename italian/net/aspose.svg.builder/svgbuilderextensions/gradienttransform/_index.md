---
title: "SVGBuilderExtensions.GradientTransform"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions GradientTransform. Imposta l'attributo gradientTransform per un elemento gradiente"
type: docs
weight: 980
url: /it/net/aspose.svg.builder/svgbuilderextensions/gradienttransform/
---
## SVGBuilderExtensions.GradientTransform<TBuilder> method

Imposta l'attributo 'gradientTransform' per un elemento gradiente.

```csharp
public static TBuilder GradientTransform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il builder dell'elemento SVG a cui viene applicato l'attributo. |
| configurare | Una funzione per configurare il builder di trasformazione SVG. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
