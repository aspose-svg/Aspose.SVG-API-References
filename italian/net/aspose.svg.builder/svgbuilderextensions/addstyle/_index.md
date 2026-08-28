---
title: "SVGBuilderExtensions.AddStyle"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo AddStyle di SVGBuilderExtensions. Aggiunge una configurazione dell'elemento style al builder"
type: docs
weight: 490
url: /it/net/aspose.svg.builder/svgbuilderextensions/addstyle/
---
## SVGBuilderExtensions.AddStyle<TBuilder> method

Aggiunge una configurazione dell'elemento 'style' al costruttore.

```csharp
public static TBuilder AddStyle<TBuilder>(this TBuilder builder, 
    Action<SVGStyleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'style'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGStyleElementBuilder](../../svgstyleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
