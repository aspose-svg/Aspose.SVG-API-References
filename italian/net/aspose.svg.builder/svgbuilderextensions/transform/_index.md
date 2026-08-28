---
title: "SVGBuilderExtensions.Transform"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions Transform. Imposta l'attributo transform per un elemento SVG"
type: docs
weight: 2260
url: /it/net/aspose.svg.builder/svgbuilderextensions/transform/
---
## SVGBuilderExtensions.Transform<TBuilder> method

Imposta l'attributo 'transform' per un elemento SVG.

```csharp
public static TBuilder Transform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, ITransformAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | Una funzione per configurare la trasformazione SVG. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITransformAttributeSetter](../../itransformattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
