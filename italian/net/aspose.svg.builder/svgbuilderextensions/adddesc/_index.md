---
title: "SVGBuilderExtensions.AddDesc"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo AddDesc di SVGBuilderExtensions. Aggiunge una configurazione dell'elemento desc al builder. L'elemento desc è usato per fornire una descrizione del contenuto SVG."
type: docs
weight: 110
url: /it/net/aspose.svg.builder/svgbuilderextensions/adddesc/
---
## SVGBuilderExtensions.AddDesc<TBuilder> method

Aggiunge una configurazione dell'elemento 'desc' al costruttore. L'elemento 'desc' è usato per fornire una descrizione del contenuto SVG.

```csharp
public static TBuilder AddDesc<TBuilder>(this TBuilder builder, 
    Action<SVGDescElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'desc'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGDescElementBuilder](../../svgdescelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
